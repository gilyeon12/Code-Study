## 22.08.08

## [🐼index1 길연 문제 ]

### [문제설명]

1. `index.html`을 생성하시오.
2. 상품을 검색하면 상품의 종류와 재고 현황을 볼 수 있는 사이트를 만드시오.
3. 다음 이미지를 보고 data()안에 `store` 리스트를 생성하시오.

![image](https://user-images.githubusercontent.com/109563072/183413873-fc5f12cf-e6f0-4770-a2f8-2e72a5a6f51e.png)

4. 상품의 이름은 `name`, 종류는 `type`, 개수는 `count`라고 하시오.
5. `label`과 `input` 속성을 사용해서 물품을 검색할 수 있도록 하시오. 이때 검색한 물품은 `product`로 하고 data()에 문자열 `product`를 생성하시오.
6. 반복문 키의 값은 `name`으로 설정하시오.
7. 제시한 참고 화면과 그대로 출력하도록 프로그램을 작성하시오.

### [문제 포인트]

- v-for
- v-if

### [출력 예시 화면]

💡초기 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414165-d1679f56-b4c5-452e-aed4-6093450e0475.png)


💡 상품을 검색 했을 때 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414249-e06f461f-4dbd-48aa-8aff-e6efa56bc446.png)


<hr/>

## [🦊index2 소연 문제 ]

### [문제설명]

1. `index1.html`을 생성하세요.
2. 지역을 검색하면 그와 관련된 리스트를 보이게 하시오.
- 리스트 이름: info
- 각 객체의 구성 키 값: loc, floor, amount, SN
- loc은 “서울”, ”대전”, ”대구”, ”부산”만 존재한다.
- 반복문의 key는 리스트의 SN로 한다.
- v-if와 v-for을 같이 쓰면 안되지만 요번만 허용하도록 한다.
3. data속성에 ‘ment에 `"고객님께 드리는 선물!! 검색해주세요!!”` 를 넣고 검색하는 순간 `"힝..속았지?”`로 변하도록 하시오.
4. “예약하러가기”를 누르면 “[https://www.naver.com](https://www.naver.com/)"로 이동하게 하시오.

### [문제 포인트]

- v-for
- v-if

### [출력 예시 화면]

💡 처음 실행 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414609-566b7575-22a6-4dfd-bb93-ddef29901411.png)

💡‘서울’검색 시 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414649-c7f9a7c8-a20d-4937-a7a7-340b0fa937f3.png)

💡‘대전’검색 시 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414688-9601751d-c4fa-4ff9-b300-c0046aa993d8.png)

💡‘대구’검색 시 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414719-1579671f-b726-45a8-9c3b-bdd2912e93f6.png)


💡‘부산’검색 시 화면<br>

![image](https://user-images.githubusercontent.com/109563072/183414744-301320e7-55d8-40f6-8b65-657c9e87de2b.png)

