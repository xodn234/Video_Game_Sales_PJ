### Project (2021.12.08 ~ 2021.12.13)
- - -
# 분석을 통한 다음 분기 제작 게임 도출

### 데이터
- 데이터 출처 : https://www.kaggle.com/datasets/gregorut/videogamesales

### 전처리
- Sales 단위 통일
- NaN 값은 다른 값으로 처리
- 이상치 데이터들이 실제 확인해본 결과 실제 맞는 데이터로 판단

### 분석과정
- ![image](https://user-images.githubusercontent.com/78893090/169694511-3bcc47c1-ad78-4138-90de-0eba24d43ada.png)
- ![image](https://user-images.githubusercontent.com/78893090/169694518-a941dc03-d9c4-40f9-a7f7-0fe5fa0daab5.png)
- 연도별 트랜드를 확인하기 위하여 각지역의 총 판매액을 연도별로  Genre와 Platform으로 만들어 데이터를 활용
- ![image](https://user-images.githubusercontent.com/78893090/169689488-d30abf7c-c68a-48fe-bba7-2a129b9b6784.png)
- ![image](https://user-images.githubusercontent.com/78893090/169694481-3c1cab90-61ae-4243-82d8-9eb5c60eb7a6.png)
- ![image](https://user-images.githubusercontent.com/78893090/169694488-4e921ef1-dfa9-41b3-93af-9802ab3987bd.png)

- 연도별 최고매출 확인
- ![image](https://user-images.githubusercontent.com/78893090/169689593-03ed800d-23b0-482e-86e2-f9e8f8b6ddb3.png)
- 이상치를 출고량이 높은게임으로 판단 (상위 이창치 계산 법 : Q3 + 1.5 *(Q3 - Q1) 이상) -> 1896종류의 데이터가 선택
- 출고량이 높은 게임들의 연도별 Size
-![image](https://user-images.githubusercontent.com/78893090/169694414-b9551109-df32-4eef-a147-222a8c720eee.png)

- 출고량이 높은 게임들의 연도별 증감 추세
-![image](https://user-images.githubusercontent.com/78893090/169694421-f0f3273e-8258-4003-8d34-9392c3fb6409.png)

### 결론
-  Genre에서는 Action이 가장 높았지만 2013년도부터 급격하게 감소하는 현상이 보였으며 대부분 2014년도부터 감소하는 경향이 있지만 Shooter이 감소폭이 작았으며 2015년도에는 최고 빈도수가 되어 Shooter를 제안하는것에 결론을 내림
-  Platform에서는 트랜드가 끝나가는 종류들이 급격하게 감소하고 있었고 최근 가장 떠오르고 있는 PS4로 제안을 하는것에 결론
- Shooter & PS4 ->  Call of Duty: Black Ops 3 -> 상위매출, 다양한 플랫폼, 최근출시 -> 좋은 참조모델 발견 
- 다음 분기에는 Call of Duty: Black Ops 3을 참조한 Shooter & PS4으로 제작을 제안
