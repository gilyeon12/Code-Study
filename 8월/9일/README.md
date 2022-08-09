## 22.08.09

## [🐼index1 길연 문제 ]

### [문제설명]

1. index.html을 생성하시오.
2. 아이디와 비밀번호를 입력하면 로그인 되는 페이지를 구현하시오.
3. 다음 이미지를 참고하여 data()를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/183616063-9ccc8b6b-c1a5-45f7-bdee-8b2406035c64.png)

4. `checkVal` 메소드와 `register` 메소드를 구현하시오.
    - 사용자의 아이디 : id123, 비밀번호 : pw123
    - `checkVal` 메소드
        - 아이디를 입력하지 않았을 때 : “아이디 입력!” 알림 문구가 뜨게 하시오.
        - 비밀번호를 입력하지 않았을 때 : “비밀번호 입력!” 알림 문구가 뜨게 하시오.
        - 아이디가 틀렸을 때 : “아이디가 틀렸습니다!” 알림 문구가 뜨게 하시오.
        - 비밀번호가  틀렸을 때 : “비밀번호가 틀렸습니다!” 알림 문구가 뜨게 하시오.
        - 둘 다 틀렸을 때 : “아이디가 틀렸습니다!” 알림 문구가 뜨게 하시오.
        - 둘 다 맞았을 때 :  `register` 메소드를 호출하시오.
    - `register` 메소드 : “로그인 완료!” 알림 문구가 뜨게 하시오. 그 후, 알림창의 확인을 누르면 data의 `username`을 “고길동”이라고 변경하시오.
    
5. 아이디와 비밀번호 입력은 `label` 과 `input` 속성을 사용하고, “로그인”이라는 문구가 들어간 `button` 을 클릭하면 `checkVal` 메소드를 호출하시오. 이때 input의 type을 변경하여 비밀번호는 text가 보이지 않게 하시오.
6.  로그인을 완료하면 `username` 이 나오는 메세지를 출력하시오.

### [문제 포인트]

- method

### [출력 예시 화면]

💡초기 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183616348-8698cca9-8da2-4d33-b56f-599ce01d1319.png)


💡 아이디가 틀렸을 때 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183616394-23386379-fc43-4787-bd9c-2956545a7d45.png)

💡 비밀번호가 틀렸을 때 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183616675-7aaed9ae-dd44-43e7-8be1-341ebdf56aee.png)

💡 둘 다 맞았을 때 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183616816-f5d92830-21fd-4b93-8bf5-d2a2cd472ca5.png)

💡 로그인 완료 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183616898-1949e9e0-9e0c-47ac-be7d-785b3ddcdb33.png)


<hr/>

## [🦊index2 소연 문제 ]

### [문제설명]

1. index.html을 생성하라.
2. 초기화면
    
![image](https://user-images.githubusercontent.com/109563072/183617362-b16c67fb-7add-4600-a63d-c123daeb1177.png)

    
3. data속성 값들
    
![image](https://user-images.githubusercontent.com/109563072/183617405-a833e4f5-7c4f-4cc5-a81c-255bd9257a2e.png)
    

### [문제 설명]

💡 <참고 이미지1>

- 번역 버튼을 누르면 trans함수가 호출되고 인트로 메시지가 영어로 바뀐다.
- 아이디를 입력하지 않으면 <참고 이미지1>과 같은 창이 뜬다.

![image](https://user-images.githubusercontent.com/109563072/183617479-dbed14b1-04b0-42f2-b0b5-6f1756ea94c0.png)

💡 <참고 이미지2>
- 아이디에 ref를 설정하고 아이디 입력란에 포커스가 옮기도록 하여라.
- 비밀번호를 입력하지 않으면 <참고 이미지2>와 같은 창이 뜬다.

![image](https://user-images.githubusercontent.com/109563072/183617540-3ee7f392-a4a6-474d-8bc6-a92a7bf904ef.png)

💡 <참고 이미지3> 아이디와 비밀번호를 입력하면 register함수가 호출된다.

![image](https://user-images.githubusercontent.com/109563072/183617616-f375b11c-699e-48b1-8051-1c8311c60992.png)

💡 <참고 이미지4> 놀이기구를 검색하면 해당 놀이기구와 대기 시간이 표시된다. 

![image](https://user-images.githubusercontent.com/109563072/183617651-c12dc225-eb14-4b77-87cd-f9e83476dec1.png)

![image](https://user-images.githubusercontent.com/109563072/183617687-6df6fd33-7f96-4db3-9e63-0cf1bd643787.png)


