# ordinal 메서드 대신 인스턴스 필드를 사용하라
## 결론
> enum 의 ordinal() 메서드 쓰지마라

## int ordinal()
- enum 열거체의 열거된 순서를 기준으로 index 값을 반환해주는 메서드

## ordinal() 을 사용하는 경우(?)
- enum 열거체에 특정 상태를 열거된 순서를 이용해서 반환하고 싶을 때 사용하는 경우가 있다.

```
public enum Ensemble {

    SOLO, DUET, TRIO, QUARTET;

    public int numberOfMusicians() {
        return ordinal() + 1;
    }

    public static void main(String[] args) {
        System.out.println(Ensemble.SOLO.numberOfMusicians()); // 1
        System.out.println(Ensemble.DUET.numberOfMusicians()); // 2
        System.out.println(Ensemble.TRIO.numberOfMusicians()); // 3
        System.out.println(Ensemble.QUARTET.numberOfMusicians()); // 4
    }
}
```

- 사용하면 안되는 이유
	- 유지보수가 힘들어진다.
		- 열거 순서가 꼬이면 ordinal() 을 활용한 메서드는 바로 오작동한다.
			- 중간에 새로운 열거체를 넣거나 빼야할 때 영향을 받는다.
	- 일정한 순서가 지켜지지 않는 열거체는 아예 사용할수도 없고 사용 하려고 해도 더미 열거체를  사용해야하는 등의 웃긴 상황이 발생한다.

## 그럼 어떡해야하나?
- 그냥 인스턴스 변수를 만들어서 사용하자.

```
public enum Rank {

    RANK_A("A", 1),
    RANK_2("2", 2), RANK_3("3", 3), RANK_4("4", 4),
    RANK_5("5", 5), RANK_6("6", 6), RANK_7("7", 7),
    RANK_8("8", 8), RANK_9("9", 9), RANK_10("10", 10),
    RANK_J("J", 10), RANK_Q("Q", 10), RANK_K("K", 10);

    private final String rank;
    private final int point;

    Rank(String rank, int point) {
        this.rank = rank;
        this.point = point;
    }
}
```

## 결론
>ordinal() 은 EnumSet, EnumMap 같은데서 사용하라고 만든 메서드이기 때문에 우리가 굳이 사용할 경우는 많지 않다.
