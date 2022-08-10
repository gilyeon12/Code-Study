## 22.08.09

## [🐼index1 길연 문제 ]

### [문제설명]

* 요한이가 친구들과 메세지를 주고 받고 있다. 요한이의 친구인 진호와 상혁이는 다음과 같이 말하는 경향이 있다.
  * 진호 : 요한이가 보내는 메세지를 붙여서 두번 출력한다.
  * 상혁 : 요한이가 보내는 메세지를 거꾸로 출력한다.

* 요한이가 보내는 메세지를 입력하면 진호와 상혁이가 보내는 메세지를 출력하는 index.html을 생성하시오.
  * reversedMsg1 : 진호가 보내는 메세지를 return하는 함수
  * reversedMsg2 : 상혁이가 보내는 메세지를 return하는 함수
* 단, method가 아닌 computed안에 reversedMsg1 과 reversedMsg2를 생성하시오.

### [문제 포인트]

- computed

### [출력 예시 화면]

![image](https://user-images.githubusercontent.com/109563072/183872016-98faa08d-7093-4146-a35e-45dc13a67e16.png)


<hr/>

## [🦊index2 소연 문제 ]

### [문제 설명]
1. index1.html을 생성하시오.

💡 초기화면

![image](https://user-images.githubusercontent.com/109563072/183872499-2cede205-67e8-4d47-92a5-7c2d4b578e4d.png)

2. 다음 이미지를 참고하여 data()를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/183872575-3e2e8a97-6125-4268-97dd-1006b21d3953.png)


3. price 필터와 call 필터를 전역 필터로 구현하시오.
  * price 필터(msg1 사용)
    * value매개변수가 없으면, value매개변수를 그대로 출력하시오.
    * value매개변수가 있으면, value를 [ /\B(?=(\d{3})+(?!\d))/g, ',’ ] 정규식으로 대체하시오.
  * call 필터(msg2 사용)
    * value매개변수가 없거나  길이가 10 또는 11이 아니라면, value매개변수를 그대로 출력하시오.
    * value매개변수가 있거나 길이가 10 또는 11이라면 , value를 [ /^(\d{3})(\d{3,4})(\d{4})/g, '$1-$2-$3’] 정규식으로 대체하시오.

4. won을 지역 필터로 구현하시오.
  * won 필터
    * value매개변수의 길이가 0이라면 alternative(대체값)을 출력하고 아니라면 금액+”원”이 보이게 하여라.

    ![image](https://user-images.githubusercontent.com/109563072/183872957-8ab21b45-4893-46b3-aa6b-fb277bab5695.png)

    ![image](https://user-images.githubusercontent.com/109563072/183873070-d9e4af14-02f6-4e36-80a6-be10e125179c.png)


5. 미국 환율 버튼을 클릭하면 trans메서드가 호출된다.
  * trans메서드
    * 버튼을 클릭하면 알림창에 계산된 환율이 보이게 한다. 1달러=1307원으로 계산한다.
    * 계산된 환율을 마지막 문장에 넣게 한다.(msg3 사용)

    ![image](https://user-images.githubusercontent.com/109563072/183873231-9ee7ca44-f99d-411d-a71e-ed01fd6fa834.png)


💡 <최종 화면>

![image](https://user-images.githubusercontent.com/109563072/183873347-d04a1e40-e4ec-429b-be47-d815b1738de4.png)

    

### [문제 포인트]

- filter
