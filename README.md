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

</div>
</details>

<details>
<summary>6장 열거 타입과 애너테이션</summary>
<div markdown="1">       

</div>
</details>

<details>
<summary>7장 람다와 스트림</summary>
<div markdown="1">       

</div>
</details>

<details>
<summary>8장 메서드</summary>
<div markdown="1">       

</div>
</details>

<details>
<summary>9장 일반적인 프로그래밍 원칙</summary>
<div markdown="1">       

</div>
</details>

<details>
<summary>10장 예외</summary>
<div markdown="1">       

</div>
</details>

<details>
<summary>11장 동시성</summary>
<div markdown="1">       

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

