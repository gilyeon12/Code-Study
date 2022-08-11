## 22.08.11

## [🐼index1 길연 문제 (할인가 계산)]

### [문제설명]

1. 상품의 원가를 입력하면 할인가를 출력하는 프로그램 index.html을 구현하시오.
2. `input` 의 타입은 `숫자`로 설정하시오.
3. 다음 이미지를 참고하여 `data()`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184121987-7844d0df-c61b-40c0-bd11-c6269d6a9af0.png)

4. 원가, A 마트 할인가, B 마트 할인가는 `p` 속성을 사용하여 구현한다.
5. A 마트와 B마트는 해당 상품을 각각 20%, 30%을 할인하고 있다. 두 마트의 할인가를 계산하는 `cal1`과 `cal2`함수를 `computed`를 사용하여 구현하시오.
6. `won` 필터를 전역 필터로 구현하시오.
  * `value`매개변수가 없다면 `value`를 그대로 출력하고, 있다면 `value`를 `[/\B(?=(\d{3})+(?!\d))/g, ',']` 정규식으로 대체하시오.
7. 원가와 A마트 할인가, B마트 할인가 모두 `won`필터를 적용하시오.

### [문제 포인트]

- computed

### [출력 예시 화면]

💡 초기화면

![image](https://user-images.githubusercontent.com/109563072/184122337-1eb011da-8e03-4bbc-bd08-62efe593bd15.png)

💡 출력 예시 화면

![image](https://user-images.githubusercontent.com/109563072/184122373-cd622d34-0b59-4189-9d50-ebc7021e8180.png)

<hr/>

## [🦊index2 소연 문제(짤랑이 뱅크)]

![image](https://user-images.githubusercontent.com/109563072/184122560-c715902b-6f2f-4132-b6dc-6c7558ddc109.png)

### [문제 설명]

1. `index1.html`을 생성하시오.

💡 초기화면

![image](https://user-images.githubusercontent.com/109563072/184122758-c9f1b3dc-0cdc-4aff-bbce-8dd4088405f2.png)

2. `input`의 `type`은 `숫자`로 설정해라.

3. 다음 이미지를 참고하여 `data()`를 구현하시오.

![image](https://user-images.githubusercontent.com/109563072/184122821-8eacb970-966f-41ca-b768-0126a6f86e01.png)

4. `price` 필터를  전역 필터로 구현하시오.
  * `price` 필터
    * `value`매개변수가 없으면, `value`매개변수를 그대로 출력하시오.
    * `value`매개변수가 있으면, `value`를 `[/\B(?=(\d{3})+(?!\d))/g, ‘,’]` 정규식으로 대체하시오.

5. `watch` 를 써서 구현하시오.
  * 미국 환율: 1달러 = 1302원
  * 중국 환율: 1위안 = 193원

6. `input`을 `숫자`로 설정했기에 위/아래 화살표를 클릭하면 전체 환율이 저절로 바뀌는 것을 확인한다.

![image](https://user-images.githubusercontent.com/109563072/184122964-c0b431d4-11a0-4503-a551-23735e297b9f.png)

💡 <최종 화면>

![image](https://user-images.githubusercontent.com/109563072/184123007-4d0a4bb1-8416-4086-bfce-c4d53f96155c.png)

### [문제 포인트]

- computed
- watch
