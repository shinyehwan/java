# java
자바 기본부터 적용까지의 연습, 정리

<br>

## CODING_JAVA
생활코딩 강의를 통한 연습 및 적용

## FAST_JAVA
- fast_campus
- JAVA 기초
- 객체 지향 프로그래밍

## LION_JAVA
- 멋사 따라 잡기 프로젝트
- 챕터별 예제를 통한 적용. 학습 설명은 상세히 주석을 달아 놓았음.
  - 챕터 0 : 개발환경 세팅
  - 챕터 1 : 변수와 출력
  - 챕터 2 : 조건문
  - 챕터 3 : 반복문
  - 챕터 4 : 클래스와 객체(+ 객체의 생사 소멸)
  - 챕터 5 : 클래스와 객체2
  - 챕터 6 : 클래스와 객체3
  - 챕터 7 : 클래스와 객체4
  - 챕터 8 : 클래스와 객체5
  - 챕터 9 : 클래스와 객체6
  - 챕터 10 : 클래스와 객체7
  - 챕터 11 : 구성
  - 챕터 12 : 구성2
  - 챕터 13 : 구성3
  - 챕터 14 : 생성자
  - 챕터 15 : 구성4
  - 챕터 16 : 구성5
  - 챕터 17 : 구성6
  - 챕터 18 : 생성자2
  - 챕터 19 : 생성자 오버로딩, 생성자 연쇄호출
  - 챕터 20 : super
  - 챕터 21 : 상수
  - 챕터 22 : 배열
  - 챕터 23 : switch
  - 챕터 24 : static
  - 챕터 25 : 형변환
  - 챕터 26 : 형변환2
  - 챕터 27 : 배열2
  - 챕터 28 : Object class
  - 챕터 29 : String Class
  - 챕터 30 : Array List
  - 챕터 31 : Array List2
  - 챕터 32 : 제너릭
  - 챕터 33 : HashMap
  - 챕터 34 : 인터페이스
  - 챕터 35 : 인터페이스 2
  - 챕터 36 : 예외처리
  - 챕터 37 : 접근제어자 시작
  - 챕터 38 : 싱글톤 패턴 끝
  - 챕터 39 : 팩토리 패턴
  - 챕터 40 : 옵저버 패턴
  - 챕터 41 : 익명 클래스
  - 챕터 42 : 내부 익명 클래스
  - 챕터 43 : 내부 익명 클래스2
  
## 기본
- 변수
```
System.out.prinln("x : " + 10 + 5)
                  "x : " + "10" + 5
                  "x : 10" + 5
                  "x : 10" + "5"
                  "x : 105"
변수, 변수가 아닌것을 구분할 줄 알아야함.
```


- 함수
- 조건문
- 반복문
## 특징
- 클래스
- 객체
- 상속
- 인터페이스 .....

### 클래스와 객체
- 모든 변수는 메모리에 저장된다.
- int 변수는 4바이트 이다.
- 변수에는 오직 8바이트 이하의 값만 넣을 수 있다.
- 객체가 필요한 이유
  - 변수에는 오직 값 1개만 넣을 수 있다.
  - 프로그래밍을 하다보면 변수에 값을 여러개 넣을 필요가 있을 때가 있다.
  - 그래서 고안된 것이 객체이다.
  - 객체는 커피 캐리어에 비유될 수 있다.
  - 커피 캐리어에는 커피를 여러잔 담을 수 있다.
  - 커피 캐리어는 용도에 따라 종류가 여러가지 있다.
  - 프로그래밍을 할 때 상황에 따라 서로 다른 종류의 객체 여러개가 필요하다.
  - 객체를 일종의 제품으로 보았을 때 객체를 만들기 위해서는 설계도 즉 클래스가 필요하다.
  - 객체는 너무 커서 변수에 담을 수 없다.
  - 그래서 또 고안된 것이 리모콘 시스템이다.
  - 클래스로는 3가지를 할 수 있다.
  - 클래스로는 객체도 만들 수 있고 그 객체를 조종할 수 있는 리모콘도 만들 수 있다. 그리고 또 객체리모콘을 담을 변수도 만들 수 있다.
- 변수에는 오직 1차원적인 값만 저장 할 수 있다.
  - 1차원 적인 값(데이터)
    - 5
    - 3.14
    - 'a'
    - true
  - 복잡한 값
    - 객체
- 변수에는 객체를 저장할 수 없다.
  - 객체가 너무 크고 변수는 작다.
  - 객체는 여러가지 값(데이터)의 조합이다. 그게 변수에 들어가면 한 덩어리로 해석된다.
  - 즉 변수에 1과 2를 넣으면, 다른 사람들은 그것을 1과 2의 조합이 아닌 12로 본다.
- **new 사람();** 을 하면 2가지가 만들어진다.
  - 객체
  - 객체가 자기자신을 조종할 수 있는 리모콘
    - 그 리모콘을 객체 스스로는 this 라고 부른다.
