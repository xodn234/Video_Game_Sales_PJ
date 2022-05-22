### Project (2022.12.08 ~ 2022.12.13)
- - -
# 다음 분기는 어떠한 게임을 제작 해야 할까?

### 데이터
- 데이터 출처 : https://www.kaggle.com/datasets/gregorut/videogamesales

### 전처리
- Sales 단위 통일
- NaN 값은 다른 값으로 처리
- 이상치 데이터들이 실제 확인해본 결과 실제 맞는 데이터로 판단

### 분석과정
- ![image](https://user-images.githubusercontent.com/78893090/169689358-e0194834-0532-4f67-8dc0-f47ea69bcd86.png)
- ![image](https://user-images.githubusercontent.com/78893090/169689377-352fe569-0761-4545-8471-fcba5a009b17.png)
- 연도별 트랜드를 확인하기 위하여 각지역의 총 판매액을 연도별로  Genre와 Platform으로 만들어 데이터를 활용
- ![image](https://user-images.githubusercontent.com/78893090/169689488-d30abf7c-c68a-48fe-bba7-2a129b9b6784.png)
- ![image](https://user-images.githubusercontent.com/78893090/169689556-808804d0-8d2d-4812-9143-c2edb8ca7296.png)
- 연도별 최고매출 확인
- ![image](https://user-images.githubusercontent.com/78893090/169689593-03ed800d-23b0-482e-86e2-f9e8f8b6ddb3.png)
- 이상치를 출고량이 높은게임으로 판단 (상위 이창치 계산 법 : Q3 + 1.5 *(Q3 - Q1) 이상) -> 1896종류의 데이터가 선택
- 연도별 증감 추세를 

- (미완)
