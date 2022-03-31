# 🍜 데일리 이펙티브 자바 스터디  

등교하는 매일 17:50~  
[이펙티브 자바](http://aladin.kr/p/1bCBy)의 아이템을 세 개씩 공부하는 모임   

## Handbook  

<details>
<summary>2장 객체 생성과 파괴</summary>
<div markdown="1">       
  
  - [정적 팩토리 메서드로 생성 목적에 맞는 객체를 생성하라](./handbook/02/01.정적%20팩토리%20메서드로%20생성%20목적에%20맞는%20객체를%20생성하라.md)  
  - [매개변수가 많으면, 빌더로 효율적이고 안전하게 생성할 수 있다](./handbook/02/02.매개변수가%20많으면%2C%20빌더로%20효율적이고%20안전하게%20생성할%20수%20있다.md)  
  - [Enum(열거타입) 방식, 또는 PRIVATE 생성자로서 인스턴스가 오직 하나뿐인 싱글턴임을 보증하라](./handbook/02/03.Enum(열거타입)%20방식%2C%20또는%20PRIVATE%20생성자로서%20인스턴스가%20오직%20하나뿐인%20싱글턴임을%20보증하라.md)  
  - [인스턴스화를 막으려거든 private 생성자를 사용하라](./handbook/02/04.인스턴스화를%20막으려거든%20private%20생성자를%20사용하라.md)  
  - [자원을 직접 명시하지 말고 의존 객체 주입을 사용하라](./handbook/02/05.자원을%20직접%20명시하지%20말고%20의존%20객체%20주입을%20사용하라.md)  
  - [불필요한 객체 생성을 피하라](./handbook/02/06.불필요한%20객체%20생성을%20피하라.md)  
  - [메모리 누수가 발생할 가능성이 있는 객체는 미리 처리하라](./handbook/02/07.메모리%20누수가%20발생할%20가능성이%20있는%20객체는%20미리%20처리하라.md)  
  - [finalizer와 cleaner 사용을 피하라. (그냥 쓰지마라)](./handbook/02/08.finalizer와%20cleaner%20사용을%20피하라.%20(그냥%20쓰지마라).md)  
  - [try-finally 보다는 try-with-resources를 사용하라](./handbook/02/09.try-finally%20보다는%20try-with-resources를%20사용하라.md)  
  
</div>
</details>

<details>
<summary>3장 모든 객체의 공통 메서드</summary>
<div markdown="1">       

  - [equals 만들 때 일반규약을 지켜라 귀찮으면 IDE가 만들어주는거 써라](./handbook/03/10.equals%20만들%20때%20일반규약을%20지켜라%20귀찮으면%20IDE가%20만들어주는거%20써라.md)  
  - [equals 를 재정의 하려거든 hashCode 도 재정의하라](./handbook/03/11.equals%20를%20재정의%20하려거든%20hashCode%20도%20재정의하라.md)  
  - [유용한 정보를 가지도록 toString을 재정의하자](./handbook/03/12.유용한%20정보를%20가지도록%20toString을%20재정의하자.md)  
  - [clone 재정의는 주의해서 진행](./handbook/03/13.clone%20재정의는%20주의해서%20진행.md)  
  - [Comparable을 구현할지 고려하라](./handbook/03/14.Comparable을%20구현할지%20고려하라.md)  
  
</div>
</details>

<details>
<summary>4장 클래스와 인터페이스</summary>
<div markdown="1">       
  
  - [클래스와 멤버의 접근 권한을 최소화하라](./handbook/04/15.클래스와%20멤버의%20접근%20권한을%20최소화하라.md)  
  - [public 클래스의 필드를 외부로 직접 노출하지 마라](./handbook/04/16.public%20클래스의%20필드를%20외부로%20직접%20노출하지%20마라.md)  
  - [변경 가능성을 최소화하라. 불변 객체를 만들자](./handbook/04/17.변경%20가능성을%20최소화하라.%20불변%20객체를%20만들자.md)  
  - [상속보다는 컴포지션과 전달을 사용하자. 래퍼클래스가 더 강력하다](./handbook/04/18.상속보다는%20컴포지션과%20전달을%20사용하자.%20래퍼클래스가%20더%20강력하다.md)  
  - [상속을 고려해 설계하고 문서화하라. 그러지 않았다면 상속은 금지하라](./handbook/04/19.상속을%20고려해%20설계하고%20문서화하라.%20그러지%20않았다면%20상속은%20금지하라.md)
  - [추상 클래스보다는 인터페이스를 우선하라](./handbook/04/20.추상%20클래스보다는%20인터페이스를%20우선하라.md)  
  - [인터페이스는 구현하는 쪽을 생각해 설계하라](./handbook/04/21.인터페이스는%20구현하는%20쪽을%20생각해%20설계하라.md)  
  - [상수 인터페이스 절대 쓰지마라](./handbook/04/22.상수%20인터페이스%20절대%20쓰지마라.md)  
  - [태그 달린 클래스보다는 클래스 계층구조를 활용하라](./handbook/04/23.%20태그%20달린%20클래스보다는%20클래스%20계층구조를%20활용하라.md)
  - [멤버 클래스는 되도록 static으로 만들라](./handbook/04/24.%20멤버%20클래스는%20되도록%20static으로%20만들라.md)  
  - [톱레벨 클래스는 한 파일에 하나만 담기](./handbook/04/25.%20톱레벨%20클래스는%20한%20파일에%20하나만%20담기.md)  
</div>
</details>

<details>
<summary>5장 제네릭</summary>
<div markdown="1">       
  
  - [로 타입은 사용하지 말라](./handbook/05/26.%20로%20타입은%20사용하지%20말라.md)  
  - [비검사 경고를 제거하라](./handbook/05/27.%20비검사%20경고를%20제거하라.md)  
  - [배열보다는 리스트를 사용하라](./handbook/05/28.%20배열보다는%20리스트를%20사용하라.md)
  - [이왕이면 제네릭 타입으로 만들라](./handbook/05/29.%20이왕이면%20제네릭%20타입으로%20만들라.md)
  - [이왕이면 제네릭 메서드로 만들라](./handbook/05/30.이왕이면%20제네릭%20메서드로%20만들라.md)
  - [한정적 와일드카드를 사용해 API 유연성을 높이라](./handbook/05/31.한정적%20와일드카드를%20사용해%20API%20유연성을%20높이라.md)
  - [제네릭과 가변인수를 함께 쓸 때는 신중해라](./handbook/05//32.%20제네릭과%20가변인수를%20함께%20쓸%20때는%20신중해라.md)
  - [타입 안전 이종 컨테이너를 고려하라](./handbook/05/33.%20타입%20안전%20이종%20컨테이너를%20고려하라.md)
</div>
</details>

<details>
<summary>6장 열거 타입과 애너테이션</summary>
<div markdown="1">
  
  - [34. int 상수 대신 열거 타입을 사용하라](./handbook/06/34.%20int%20상수%20대신%20열거%20타입%20써라.md)  
  - [35. ordinal 메서드 대신 인스턴스 필드를 사용하라](./handbook/06/35.%20ordinal%20메서드%20대신%20인스턴스%20필드를%20사용하라.md)
  - [36.비트 필드 대신 EnumSet을 사용하라](./handbook/06/36.%20비트%20필드%20대신%20EnumSet을%20사용하라.md)
  - [37. ordinal 인덱싱 대신 EnumMap을 사용하라](./handbook/06/37.%20ordinal%20인덱싱%20대신%20EnumMap을%20사용하라.md)
  - [38. 확장할 수 있는 열거 타입이 필요하면 인터페이스를 사용하라](./handbook/06/확장할%20수%20있는%20열거%20타입이%20필요하면%20인터페이스를%20사용하라.md)
  - [39. 명명 패턴보다 애너테이션을 사용하라](./handbook/06/39%20명명%20패턴보다%20애너테이션을%20사용하라.md)  
  - [40. 재정의 할 때는 항상 Override 애너테이션을 붙여라](./handbook/06/40.%20재정의%20할%20때는%20항상%20%20%40Override%20애너테이션을%20붙여라.md)  
  - [41. 정의하려는 것이 타입이라면 마커 인터페이스를 사용하라](./handbook/06/41.%20정의하려는%20것이%20타입이라면%20마커%20인터페이스를%20사용하라.md)  
  - [42. 익명 클래스 보다는 람다를 사용하라](./handbook/06/42.익명%20클래스%20보다는%20람다를%20사용하라.md)  
  - [43. 람다보다는 메서드 참조를 사용하라](./handbook/06/43.%20람다보다는%20메서드%20참조를%20사용하라.md)  
</div>
</details>

<details>
<summary>7장 람다와 스트림</summary>
<div markdown="1">       
  
  - [44. 표준 함수형 인터페이스를 사용하라](./handbook/07/44.%20표준%20함수형%20인터페이스를%20사용하라.md)  
  - [45. 스트림은 주의해서 사용하라](./handbook/07/45.%20%EC%8A%A4%ED%8A%B8%EB%A6%BC%EC%9D%80%20%EC%A3%BC%EC%9D%98%ED%95%B4%EC%84%9C%20%EC%82%AC%EC%9A%A9%ED%95%98%EB%9D%BC.md) 
  - [46. 스트림에서는 부작용 없는 함수를 사용하라](./handbook/07/46.%20스트림에서는%20부작용%20없는%20함수를%20사용하라.md)  
  - [47. 반환 타입으로는 스트림보다 컬렉션이 낫다](./handbook/07/47.%20반환%20타입으로는%20스트림보다%20컬렉션이%20낫다.md)  
  - [48. 스트림 병렬화는 주의해서 적용하라](./handbook/07/48.%20스트림%20병렬화는%20주의해서%20적용하라.md)  

</div>
</details>

<details>
<summary>8장 메서드</summary>
<div markdown="1"> 
  
  - [49. 매개변수가 유효한지 검사하라](./handbook/08/49.%20매개변수가%20유효한지%20검사하라.md)  
  - [50. 적시에 방어적 복사본을 만들라](./handbook/08/50.%20적시에%20방어적%20복사본을%20만들라.md)  
  - [51. 메서드 시그니처를 신중히 설계하라](./handbook/08/51.%20메서드%20시그니처를%20신중히%20설계하라.md)  
  - [52. 다중정의는 신중히 사용하라](./handbook/08/52.%20다중정의는%20신중히%20사용하라.md)  
  - [53. 가변인수는 신중히 사용하라](./handbook/08/53.가변인수는%20신중히%20사용하라.md)  
  - [54. null이 아닌, 빈 컬렉션이나 배열을 반환하라](./handbook/08/54.%20null이%20아닌%2C%20빈%20컬렉션이나%20배열을%20반환하라.md)  
  
</div>
</details>

<details>
<summary>9장 일반적인 프로그래밍 원칙</summary>
<div markdown="1">       

  - [61. 박싱된 기본 타입보다는 기본 타입을 사용하라](./handbook/09/61.%20박싱된%20기본%20타입보다는%20기본%20타입을%20사용하라.md)  
  - [65. 리플렉션 보다는 인터페이스를 사용하라](./handbook/09/65.%20리플렉션%20보다는%20인터페이스를%20사용하라.md)
  
</div>
</details>

<details>
<summary>10장 예외</summary>
<div markdown="1">       

  - [75. 예외의 상세 메시지에 실패 관련 정보를 담으라](./handbook/10/75.%20예외의%20상세%20메시지에%20실패%20관련%20정보를%20담으라.md)

</div>
</details>

<details>
<summary>11장 동시성</summary>
<div markdown="1">       

  - [80. 스레드보다는 실행자, 태스크, 스트림을 애용하라](./handbook/11/80.%20스레드보다는%20실행자%2C%20태스크%2C%20스트림을%20애용하라.md)
  
</div>
</details>

<details>
<summary>12장 직렬화</summary>
<div markdown="1">       

</div>
</details>

## Members  

|[![](https://github.com/hyewoncc.png?size=80)](https://github.com/hyewoncc)|[![](https://github.com/jaejae-yoo.png?size=80)](https://github.com/jaejae-yoo) |[![](https://github.com/BETTERFUTURE4.png?size=80)](https://github.com/BETTERFUTURE4) | [![](https://github.com/kbsat.png?size=80)](https://github.com/kbsat) | [![](https://github.com/nbalance97.png?size=80)](https://github.com/nbalance97) |  
|:---:|:---:|:---:|:---:|:---:|
| 써머 | 그린론 | 헌치 | 로마 | 라쿤 |  


|[![](https://github.com/sojukang.png?size=80)](https://github.com/sojukang)|[<img src="https://github.com/woong7.png" width="80">](https://github.com/woong7) |[![](https://github.com/SuyeonChoi.png?size=80)](https://github.com/SuyeonChoi) | [![](https://github.com/jojogreen91.png?size=80)](https://github.com/jojogreen91) | [![](https://github.com/Byeongju-Kong.png?size=80)](https://github.com/Byeongju-Kong) |  
|:---:|:---:|:---:|:---:|:---:|  
| 소주캉 | 판다 | 페퍼 | 조조그린 | 크리스 |  


|[![](https://github.com/RunaNam.png?size=80)](https://github.com/RunaNam)|[![](https://github.com/devHudi.png?size=80)](https://github.com/devHudi) |[![](https://github.com/RIANAEH.png?size=80)](https://github.com/RIANAEH) | [<img src="https://github.com/sc0116.png" width="80">](https://github.com/sc0116) | [![](https://github.com/awesomeo184.png?size=80)](https://github.com/awesomeo184) |  
|:---:|:---:|:---:|:---:|:---:|  
| 루나 | 후디 | 엘리 | 짱구 | 어썸오 |  

