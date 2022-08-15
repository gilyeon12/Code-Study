## 22.08.12

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
