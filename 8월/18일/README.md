## 22.08.18

## [🐼index1 길연 문제(사자성어 퀴즈)]

### [문제설명]

1. `index.html` 을 생성하시오.

2. 다음과 같은 사자성어 퀴즈 페이지를 구현하시오.

<참고 화면 1 - 초기 화면>

![image](https://user-images.githubusercontent.com/109563072/185632840-c68eb133-be1d-41c8-9521-7e3802776d08.png)

3. 이 페이지는 id가 `app`이라는 div안에 id가 `ChildComp`라는 컴포넌트 5개로 구성되어있다.

![image](https://user-images.githubusercontent.com/109563072/185632911-9896542e-6a82-4802-bb1f-4cb092ff0218.png)

4. id가 `app`이라는 div의 data는 다음과 같다.

![image](https://user-images.githubusercontent.com/109563072/185632993-2d2fda4d-0936-48bf-987b-38c0b8d62606.png)


5. props을 이용하여 app의 data인 `numbers`와 `result`를 `childComp`에 전달하시오.

- `numbers`- type : String형

- `result`- type : String형, require: true


6. `childComp`에서 `numbers`와 `result`를 출력할 때 `v-for`를 이용하여 출력하시오.

7. `childComp`에서 `numbers`를 담은 버튼을 클릭하면 `select`라는 메서드를 호출하시오.

- `select` 메서드

    - 클릭한 버튼의 `numbers`가 “c”라면, “정답입니다!”라는 알림창을 출력하시오.

    - 클릭한 버튼의 `numbers`가 “c”  가 아니라면, “틀렸습니다!”라는 알림창을 출력하시오.

![image](https://user-images.githubusercontent.com/109563072/185633310-5d560d9f-2e4b-4891-8eb3-5a8bd585a91e.png)

![image](https://user-images.githubusercontent.com/109563072/185633334-ff4b0f96-b098-4b50-b05f-2c51e7a016e1.png)


### [문제 포인트]

- component간 통신

<br>

### [알게된 점]

- 컴포넌트를 호출할 때 `v-for`를 쓰면 컴포넌트와 함께 컴포넌트의 데이터도 여러 개 불러올 수 있다.

<br>

<hr/>

## [🦊index2 소연 문제(괌이 좋아요)]

1. `index.html` 을 생성하시오.

<참고 화면 1 - 초기 화면>

![image](https://user-images.githubusercontent.com/109563072/185633940-c6817206-c2f3-4159-b744-a7d713cf891f.png)

2. 다음 이미지를 참고하여 data를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/185634019-5189c40e-660a-4a9f-b826-13d09c0275f4.png)

3. 컴포넌트

- 이름: `childcomp`는 **‘파스칼 표기법’** 으로 작성하여라.

- 탬플릿: `ChildComp`라는 아이디로 설정하고 탬플릿을 따로 빼라.

  - 탬플릿 영역

![image](https://user-images.githubusercontent.com/109563072/185634150-6a9600a3-8256-4045-97a0-34718ad9a572.png)

- props:

  - `country`: 문자열, 필수값

  - `msg`: 문자열, 필수값

- 메서드: `check()`

  - 나라 이름이 ‘괌’’이면서 메시지가 ‘좋아요’라면 알림창에 ‘정답’이라고 뜬다.

  - 아니라면 알림창에 ‘실패’라고 뜬다.

![image](https://user-images.githubusercontent.com/109563072/185634364-1fc51c5e-6ef0-4eb7-aae4-a40afb54b0c6.png)

![image](https://user-images.githubusercontent.com/109563072/185634379-e6f69b7f-2ae2-4639-abbd-55dc392a3428.png)

4. `country`와 `msg`는 5의 배수(*5)로 랜덤으로 나오게 한다.

<br>

### [문제 포인트]

- component간 통신
