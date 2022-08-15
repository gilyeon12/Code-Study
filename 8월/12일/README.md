## 22.08.15

## [🐼index1 길연 문제 (To Do List)]

### [문제설명]

1. `index.html`을 생성하시오.

2. 다음과 같은 **To Do List**를 구현하려고 한다.

💡 초기화면

![image](https://user-images.githubusercontent.com/109563072/184618848-7ee192ff-cc67-48cc-9556-5e980568ad0a.png)


3. 다음 이미지를 참고하여 `data`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184618880-fa18cbdb-6f53-4519-b0ca-0c2cda9204a5.png)

4. `ul` 태그를 사용하여 `data`의 `todos`가 순서가 없는 리스트로 구현되도록 하시오.

5. 다음 이미지를 참고하여 `style`에 `completed`라는 클래스를 생성하시오.

![image](https://user-images.githubusercontent.com/109563072/184618891-fd621153-e5d2-4092-93c6-5fa3415082a3.png)

6. 각 목록 리스트인 `li`에 `v-bind`를 사용하여 `data`의 `mystyle`과 `style`의 `completed` 클래스를 적용하시오.

7. `method`에 `todo`의 객체를 인자값으로 갖는 `complete` 메소드를 구현하시오.

  - complete 메소드

      (1) todo의 `done`이 `fasle`라면, `done`을 `true`로 바꾸고 버튼 안에 텍스트를 "취소"로 바꾸어라.

      (2) todo의 `done`이 `true`라면, `done`을 `fasle`로 바꾸고 버튼 안에 텍스트를 "완료"로 바꾸어라.

8. 각 목록 옆에 버튼을 생성하고 클릭하여 `todo`의 목록을 인자값으로 갖는 `complete` 메소드를 호출하시오.

### [문제 포인트]

- style에 v-bind 적용하기

### [출력 예시 화면]

💡 출력 예시 화면 - 버튼을 클릭했을 때

![image](https://user-images.githubusercontent.com/109563072/184619165-938f025e-877f-4215-984a-a0109e06ca18.png)

💡 출력 예시 화면 - 완료된 목록의 버튼을 다시 클릭했을 때

![image](https://user-images.githubusercontent.com/109563072/184619178-e35bcd4f-40d2-4a35-b33d-536f081ae06a.png)

<hr/>

## [🦊index2 소연 문제(의류 관리 사이트)]

### [문제설명]

1. `index1.html`을 생성하시오.

💡 초기화면

- 비밀번호는 `input`에서 안 보이게 설정해라.

![image](https://user-images.githubusercontent.com/109563072/184619836-51445d0a-9854-447e-af40-22936dc83fb2.png)

<br>
2. 다음 이미지를 참고하여 `data`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184619889-8130c43d-aaa3-4219-9d32-6586ed665016.png)

<br>
3. 아이디와 비밀번호 폼

- 확인 버튼을 누르면 http://www.naver.com으로 이동하게 설정하라.

- 아이디와 비밀번호 유효성 검사를 하고 밑에 문구가 출력 되게 하여라.

    - 아이디에서 타자를 칠 때마다 `idCheck` 함수를 호출하게 하여라.
    - 비밀번호에서 타자를 칠 때마다 `pwCheck` 함수를 호출하게 하여라.
<br>

4. 아이디 체크 함수(idCheck)

- id는 5자리 이상 12자리 이하이다.

![image](https://user-images.githubusercontent.com/109563072/184620034-eef07a27-9a9e-4030-b16f-c74a492bbe29.png)


- “admin”이라는 id는 사용할 수 없다.

![image](https://user-images.githubusercontent.com/109563072/184620068-b7540b41-f876-4941-846e-6ef1e921f1fb.png)

- 그 외는 모두 사용 가능하다.

![image](https://user-images.githubusercontent.com/109563072/184620099-9e93fe4d-93f9-4e51-a75c-b30df5e04677.png)
<br>

5. 비밀번호 체크 함수(pwCheck)

- 비밀번호는 8자리 이상 20자리 이하이다.

![image](https://user-images.githubusercontent.com/109563072/184620150-7de74e1f-ff53-4fca-858e-bf63a3571579.png)

- 아이디와 비밀번호가 동일하면 사용할 수 없다.

![image](https://user-images.githubusercontent.com/109563072/184620184-3d6a046d-1003-4f5a-a9f3-80b933721eb1.png)

- 그 외는 모두 사용 가능하다.

![image](https://user-images.githubusercontent.com/109563072/184620198-5aa86ef0-7082-4a5a-8c2a-6baf6ba79fac.png)

<br>

6. 재고 검색

- 반복문의 `key`는 `cloths`의 `SN`으로 설정하여라.

- 분류 중에 선택해서 검색하면 해당 재고가 나온다.

![image](https://user-images.githubusercontent.com/109563072/184620242-9c2796b4-30b9-46d3-84b3-9d63b709a2c9.png)

![image](https://user-images.githubusercontent.com/109563072/184620256-c45a063b-5204-47bc-b1e5-ac288e0c6aa0.png)

<br>

7. 발주 폼

- 발주1 버튼

    - 전달 인자: `안녕하세요 발주1`  / 매개변수: `msg`

![image](https://user-images.githubusercontent.com/109563072/184620318-43fe0d4f-fb4a-4870-8f88-cc75505837b5.png)

    - 버튼을 클릭하면 http://www.google.com으로 이동한다.

- 발주2 버튼

    - 전달 인자: `이벤트`, `안녕하세요 발주2` /  매개변수: `e`, `msg`

![image](https://user-images.githubusercontent.com/109563072/184620394-f0e62bf7-9cf8-40ee-8040-16edd0f2ad7b.png)

  - 버튼을 클릭하면 이벤트 함수로 페이지 이동을 막는다.

  - 알림창이 뜨면 버튼이 ‘발주완료’로 바뀐다.

![image](https://user-images.githubusercontent.com/109563072/184620525-ba68ef73-ccdc-4b50-a9a4-04a30918409b.png)


- 발주3 버튼

    - 전달 인자: `없음` /  매개변수: `없음`

![image](https://user-images.githubusercontent.com/109563072/184620483-e272e6cc-4ae8-46bf-ac94-ffda127c5ded.png)


  - 클릭하면 `prevent`로 이동을 막는다.

  - 알림창이 뜨면 버튼이 ‘발주완료’로 바뀐다.

![image](https://user-images.githubusercontent.com/109563072/184620513-4bc7f597-8069-4ac3-8497-c149492b6927.png)

