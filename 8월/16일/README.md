## 22.08.16

## [🐼index1 길연 문제(회원 가입)]

### [문제설명]

1. `index.html` 을 생성하시오.

2. 다음과 같은 회원 가입 폼을 구현하시오.

<참고 화면 1 - 초기 화면>

![image](https://user-images.githubusercontent.com/109563072/184884222-f3a6984c-be00-41d4-ac09-7152ca291fbb.png)

3. 다음 이미지를 참고하여 `data`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184884252-7fe0da20-e931-4f7c-9312-42d592e1463b.png)

4. 아이디 중복 확인
- `input` 속성에 아이디를 입력하고 중복 확인 버튼을 클릭하면 `ckID` 라는 메소드를 호출하시오.
- `ckID` 메소드

(1) 입력한 아이디가 **admin**이라면 **"중복된 아이디입니다.”**라는 알림창이 뜬다.

(2) 중복되지 않았다면 **“아이디 중복 확인이 완료 되었습니다.”**라는 알림창이 뜬다.

![image](https://user-images.githubusercontent.com/109563072/184884469-d9ff61f6-fbe0-45ad-a9b0-a7eadb6ad0b5.png)

(3) 알림창의 확인 버튼을 누르면 중복 확인 버튼의 문구가 **“확인 완료”**라고 바뀐다.

![image](https://user-images.githubusercontent.com/109563072/184884635-17aa881c-144b-46bc-8d34-15e6fdc3b06a.png)


5. 비밀번호 확인

- `input` 속성에 비밀번호를 입력하고 중복 확인 버튼을 클릭하면 `ckPW`라는 메소드를 호출하시오.
- `ckPW`메소드

(1) 입력한 비밀번호와 비밀번호 확인칸에 입력한 비밀번호가 같다면 **"비밀번호가 확인 되었습니다.”** 라는 알림창이 뜬다. 

![image](https://user-images.githubusercontent.com/109563072/184884677-0aa6fe3d-036e-44a6-ad8c-67f714a361ba.png)


(2) 알림창의 확인 버튼을 누르면 비밀번호 확인 버튼의 문구가 **“확인 완료”**라고 바뀐다.

![image](https://user-images.githubusercontent.com/109563072/184884716-ee64e958-3f62-43b1-af76-902d82968406.png)


(3) 반면에 버튼을 눌렀을 때 비밀번호가 다르다면 **"비밀번호가 다릅니다.”** 라는 알림창이 뜬다.

![image](https://user-images.githubusercontent.com/109563072/184884745-c30f7a97-3739-4a54-8e10-6aa84cd96aaa.png)


6. 이름, 핸드폰 번호, 이메일은 모두 `input`의 `text`로 구현한다.

7. 성별은 `radio button`으로 구현하여 남자, 여자 중 하나만 선택할 수 있도록 한다.

8. 수신 동의는 `checkbox`로 구현하여 중복 체크할 수 있도록 한다.

9. 회원 가입 버튼을 누르면 `checkVal`이라는 메소드를 호출한다.

- `checkVal` 메소드

(1) 아이디를 입력하지 않았으면 **"아이디 입력!”** 이라는 알림창이 뜨도록 한다.

(2) 아이디를 중복 확인하지 않았으면 **"아이디를 다시 확인해주세요.”** 이라는 알림창이 뜨도록 한다.

(3) 비밀번호를 입력하지 않았으면 **"비밀번호 입력!”** 이라는 알림창이 뜨도록 한다.

(4) 비밀번호를 확인하지 않았으면 **"비밀번호를 다시 확인해주세요.”** 이라는 알림창이 뜨도록 한다.

(5) 이름을 입력하지 않았으면 **"이름 입력!”** 이라는 알림창이 뜨도록 한다.

(6) 핸드폰 번호를 입력하지 않았으면 **"핸드폰 번호 입력!”** 이라는 알림창이 뜨도록 한다.

(7) 이메일을 입력하지 않았으면 **"이메일 입력!”** 이라는 알림창이 뜨도록 한다.

(8) 성별을 체크하지 않았으면 **"성별 체크!”** 이라는 알림창이 뜨도록 한다.

(9) 모두 다 확인했으면 `register`메소드를 호출한다.

- `register`메소드

(1) 알림창에 **"(사용자의 이름)님 가입해주셔서 감사합니다.”** 라는 알림창이 뜨도록 한다.

![image](https://user-images.githubusercontent.com/109563072/184884925-c9d2c8ed-8835-47e8-a0e5-26518335966e.png)


### [문제 포인트]

- input binding


<hr/>

## [🦊index2 소연 문제(상상만으로 행복한 설문조사)]

### [문제설명]

1. `index1.html`을 생성하시오.

<초기화면>

![image](https://user-images.githubusercontent.com/109563072/184885834-383f61b9-5f40-412e-abc8-1520520957ed.png)


2. 다음 이미지를 참고하여 `data`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184885863-e4f9ce15-fbc1-4ed8-a6c2-17d7c231742a.png)


3. 이름/나이/편지

- 이름 입력 칸 : 앞, 뒤 공백을 제거하도록 설정하여라.

- 나이 입력 칸 : 칸 안에는`text`도 쓸 수 있으나, 입력하면 숫자로 전달하게 설정하여라.

- 편지 쓰는 칸 :
  - 크기(가로: 30/세로:0)

  - 편지를 다 쓰고 난 후에야 메시지가 출력 되게 만들어라. 

![image](https://user-images.githubusercontent.com/109563072/184885968-d0202c90-10a9-4cb6-b616-5bae6ad47e31.png)

<br>

4. 이메일/문자 수신

- 이메일:

  - 수신O: “Yes” / 수신X: “No”

  - 미리 체크가 되어 있다.

- 문자:

  - 수신O: “네” / 수신X: “아니오”

  - 미리 체크가 되어 있다.

![image](https://user-images.githubusercontent.com/109563072/184886179-383d7059-ceec-4696-a836-5d5248529aef.png)


<br>

5. 가고 싶은 여행지(데이터: `checkedArea`)

- 중복 선택 가능

- value: `India/Japan/Guam/Canada/Thailand`

![image](https://user-images.githubusercontent.com/109563072/184886212-8ea2fa4f-9b77-4786-b43b-a12963ac2710.png)

<br>

6. 가장 가고 싶은 여행지(데이터: `checkedArea2`)

- 중복 선택 불가능

- value: `India/Japan/Guam/Canada/Thailand`

![image](https://user-images.githubusercontent.com/109563072/184886306-7a0d4e3d-26b1-4486-af3e-a41a5aebbab8.png)

<br>

7. 10년 뒤 나에게 가장 필요한 것은?(데이터: `selectAfter`)

- 중복 선택 가능

- 맨 위에는 **“선택하세요”**는 선택할 수 없도록 한다.

- value: `honor/money/power/happiness/family`

![image](https://user-images.githubusercontent.com/109563072/184886377-3aacfb3a-7f42-43b8-a1cd-5bf7da2e9c28.png)

<br>

8. 가장 필요한 것은?(데이터: `selectNow`)

- 반복문으로 `select`박스가 한 줄만 보이게 설정하여라

![image](https://user-images.githubusercontent.com/109563072/184886456-b6c94bb3-0fac-4e1b-b31d-972850883524.png)


- 화면이 뜨자마자 `‘job’`이 보이게 한다.

- `select`가 열렸을 때 참고 화면

![image](https://user-images.githubusercontent.com/109563072/184886497-8386099a-c123-41bd-a948-2a9cf31ce9d6.png)

### [문제 포인트]

- input binding

