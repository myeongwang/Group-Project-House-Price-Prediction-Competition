[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/g6ZC_OOE)

# House Price Prediction Competition 
<img width="1023" alt="스크린샷 2024-01-25 오후 8 59 34" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/3dfff23e-49f6-47a7-a200-901ac4df1d4c">

## Team

| ![이명진](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/116725865/0fca01d5-ef06-429b-86b5-314c4a0844e9) | ![서재현](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/116725865/df7f4ae6-afdb-4624-b130-88f68ce6ad1a) | ![신주용](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/116725865/6d047df8-b648-4b4b-8180-db4d61d3a30d) | ![이영훈](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/116725865/fed64993-4c58-4223-9e10-8a942e1a03c2) | ![이준형](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/116725865/66b20948-1eec-4273-9eb4-9d393221cfb8) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [이명진](https://github.com/myeongwang)             |            [서재현](https://github.com/SeoJaeHyeon)             |            [신주용](https://github.com/kimddong23)             |            [이영훈](https://github.com/ANGHOOO)             |            [이준형](https://github.com/Perelman-0)             |
|                            **팀장, EDA, Feature Engineering, Modeling**                             |                           **EDA, Feature Engineering, Modeling**                           |                         **EDA, Feature Engineering, Modeling**                           |                            **EDA, Feature Engineering, Modeling**                      |                            **EDA, Feature Engineering, Modeling**                             |

##  :clipboard: Stacks 
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white"> <img src="https://img.shields.io/badge/Anaconda-44A833?style=for-the-badge&logo=Anaconda&logoColor=white"> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white"> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google colab&logoColor=white">  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=NumPy&logoColor=white"> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"> <img src="https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=Polars&logoColor=white"> <img src="https://img.shields.io/badge/scikit-learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"> <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <img src="https://img.shields.io/badge/Zoom-0B5CFF?style=for-the-badge&logo=Zoom&logoColor=white"> <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=Canva&logoColor=white">

## 1. Competiton Info

### Overview

- **House Price Prediction | 아파트 실거래가 예측**
- 서울시 아파트 실거래가 매매 데이터를 기반으로 아파트 가격을 예측하는 대회
  
<img width="500" alt="스크린샷 2024-01-18 오후 2 39 56" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/3a6076ac-60ea-434a-87ba-e67ed97fa041"><img width="500" alt="스크린샷 2024-01-18 오후 2 39 42" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/3e1136d0-6f0b-4abc-8960-ee9a427e7850">

부동산은 의식주에서의 주로 중요한 요소 중 하나입니다. 이러한 부동산은 아파트 자체의 가치도 중요하고, 주변 요소 (강, 공원, 백화점 등)에 의해서도 영향을 받아 시간에 따라 가격이 많이 변동합니다. 개인에 입장에서는 더 싼 가격에 좋은 집을 찾고 싶고, 판매자의 입장에서는 적절한 가격에 집을 판매하기를 원합니다. 부동산 실거래가의 예측은 이러한 시세를 예측하여 적정한 가격에 구매와 판매를 도와주게 합니다. 그리고, 정부의 입장에서는 비정상적으로 시세가 이상한 부분을 체크하여 이상 신호를 파악하거나, 업거래 다운거래 등 부정한 거래를 하는 사람들을 잡아낼 수도 있습니다. 

저희는 이러한 목적 하에서 다양한 부동산 관련 의사결정을 돕고자 하는 부동산 실거래가를 예측하는 모델을 개발하는 것입니다. 특히, 가장 중요한 서울시로 한정해서 서울시의 아파트 가격을 예측하려고합니다.

참가자들은 대회에서 제공된 데이터셋을 기반으로 모델을 학습하고, 서울시 각 지역의 아파트 매매 실거래가를 예측하는데 중점을 둡니다. 이를 위해 선형 회귀, 결정 트리, 랜덤 포레스트, 혹은 딥 러닝과 같은 다양한 regression 알고리즘을 사용할 수 있습니다.

제공되는 데이터셋은 총 네가지입니다. 첫번째는 국토교통부에서 제공하는 아파트 실거래가 데이터로 아파트의 위치, 크기, 건축 연도, 주변 시설 및 교통 편의성과 같은 다양한 특징들을 포함하고 있습니다. 두번째와 세번째 데이터는 추가 데이터로, 서울시에서 제공하는 지하철역과 버스정류장에 대한 다양한 정보들을 포함하고 있습니다. 마지막 네번째 데이터는 평가 데이터로, 최종 모델성능에 대한 검증을 위해 사용됩니다.

참가자들은 이러한 다양한 변수와 데이터를 고려하여 모델을 훈련하고, 아파트의 실거래가에 대한 예측 성능을 높이기 위한 최적의 방법을 찾아야 합니다.

경진대회의 목표는 정확하고 일반화된 모델을 개발하여 아파트 시장의 동향을 미리 예측하는 것입니다. 이를 통해 부동산 관련 의사 결정을 돕고, 효율적인 거래를 촉진할 수 있습니다. 또한, 참가자들은 모델의 성능을 평가하고 다양한 특성 간의 상관 관계를 심층적으로 이해함으로써 데이터 과학과 머신 러닝 분야에서의 실전 경험을 쌓을 수 있습니다.

본 대회는 결과물 csv 확장자 파일을 제출하게 됩니다.

input : 9,272개의 아파트 특징 및 거래정보

output : 9,272개의 input에 대한 예상 아파트 거래금액




### Timeline

- ex) January 15, 2024 - Start Date
- ex) January 25, 2024 - Final submission deadline

### Evaluation

- 해당 시점의 매매 실거래가를 예측하는 Regression 대회이며, 평가지표는 RMSE(Root Mean Squared Error)를 사용합니다.
<img width="539" alt="스크린샷 2024-01-18 오후 2 54 04" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/e1ec2b35-cb45-4070-9289-fdfa1fd2c50b">

- RMSE는 예측된 값과 실제 값 간의 평균편차를 측정합니다. 아파트 매매의 맥락에서는 회귀 모델이 실제 거래 가격의 차이를 얼마나 잘 잡아내는지 측정합니다. 

## 2. Components

### Directory
![스크린샷 2024-01-25 오후 8 52 25](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/ecf592bd-d0a3-433e-b0da-e1e3a5de7fcf)



## 3. Data descrption

### Dataset overview

주요 데이터는 .csv 형태로 제공되며, 서울시 아파트의 각 시점에서의 거래금액(만원)을 예측하는 것이 목표입니다.

학습 데이터는 아래와 같이 1,118,822개이며, 예측해야 할 거래금액(target)을 포함한 52개의 아파트의 정보에 대한 변수와 거래시점에 대한 변수가 주어집니다.

<img width="500" alt="스크린샷 2024-01-18 오후 2 58 52" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/6ea70113-72bb-4263-8029-e7bf2b5efb1a">

학습 데이터의 기간은 2007년 1월 1일부터 2023년 6월 30일까지이며, 각 변수 명이 한글로 되어있어 어떤 정보를 나타내는 변수인지 쉽게 확인할 수 있습니다.

예시)
- 시군구 : “서울특별시 강남구 개포동” 과 같이 주소에 대한 정보입니다.
- 아파트명 : “개포더샵트리에”와 같이 아파트명에 대한 정보입니다.
- 전용면적(㎡) : “108.2017”와 같이 매매대상의 전용면적에 대한 정보입니다.
- 건축년도 : “2021”과 같이 아파트의 건축 연도를 나타내는 정보입니다.

각 변수들은 아래와 같은 결측치 비율을 가지고 있습니다.

<img width="500" alt="스크린샷 2024-01-18 오후 2 59 16" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/cf7266b5-2eb3-4a9e-ab81-c53174cafb54">

아파트의 매매가를 결정하는데에 교통적인 요소가 영향을 줄 수 있기에 추가 데이터로 서울시 지하철역, 서울시 버스정류장의 정보가 주어집니다. 

<img width="500" alt="스크린샷 2024-01-18 오후 2 59 52" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/4314505a-3c92-46ce-9cfe-535761fe5f10">

추가 데이터는 위도와 경도, 좌표 X와 좌표Y와 같이 거리에 대한 정보가 포함되어 있으며, 이를 활용하여 학습 데이터와 함께 사용할 수 있습니다. 

### EDA & Feature Engineering 

####  < feature 요약 > 
- k-복도유형, k-난방방식, 시군구, 전용면적, 계약일, 층, 건축년도, k-전체동수, k-전체세대수 등 53개 column이 존재
- 대부분의 결측치가 존재하는 열은 약 100만개 데이터 중 약 87만개가 결측치
-서울시 건축물 대장 데이터에서 도로명 주소를 기반으로 결측치를 채움
- 이외 여러 새로운 feature를 추가

#### < 전용면적 feature >
![스크린샷 2024-01-25 오후 4 39 45](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/0fa6fe80-827a-409f-ac0d-ab7b53e80003)

- 전용 면적이 클수록 아파트 가격이 상대적으로 높음
- 전용 면적이 작을수록 아파트 가격이 상대적으로 낮음
- 전용 면적과 아파트 가격인 target은 서로 양의 상관관계를 가지고 있음  

#### < 한강거리 feature >
![스크린샷 2024-01-25 오후 3 48 04](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/36c80e6b-bb62-4896-a9b9-b6184e067afb)
![스크린샷 2024-01-25 오후 3 47 50](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/edf30530-3926-4100-b866-003559bbb122)

- 각 아파트 X, Y를 기준으로 한강의 Y좌표만을 가지고 한강과의 거리 계산
- 한강거리와 target의 분포를 보면,서로 음의 상관관계를 가짐

#### < 구별 1인당 평균 급여 feature >
![스크린샷 2024-01-25 오후 3 51 44](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/52a8dca2-a5a2-433d-94c2-b80d738e1b51)

- 국가통계포털 KOSIS의 시군구별 근로소득 연말정산 신고현황 데이터 활용
- 금액 / 인원 = 1인당 평균급여(구 별)
- 16~21년도의 서울시 구 별 1인당 평균급여 계산한 피처 추가 
- 22~23년  Linear Regression으로 추론
  
#### < 동일 아파트 내 전용면적 타입비율 feature >
![스크린샷 2024-01-25 오후 3 55 34](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/4cf44209-4010-44fa-985c-25a5c7d973f9)

- 특정 면적 타입의 세대 수를 총 세대 수로 나누어 아파트당 타입 비율을 계산
- (0, 30), (30, 60), (60, 90), (90, 120), (120~)  5개의 범위로 나누어 해당 아파트의 타입 비율 계산 
- 해당 아파트가 속하는 전용면적 비율 추적가능(넓은 평수가 많이 해당되어 있는 아파트인지)

#### < 복도유형 feature >
![스크린샷 2024-01-25 오후 4 29 56](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/98a249bf-62a0-4486-88db-799f7b625f82)


- ‘복도유형’ 카테고리별로 년도에 따라 실거래가 추이가 다르게 나타남
- 이를 통해 ‘복도유형' 카테고리가 실거래가를 예측하는데 주요한 변수로 작용할 것이라 예상
- 복도유형 별 전용면적의 평균값으로 구간을 나눠서 각 구간에 따라 복도유형의 결측치 값을 채우는 방식으로 진행

#### < 일정 거리 내의 버스 정류장 개수의 총합 feature >
![스크린샷 2024-01-25 오후 3 59 32](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/29297188-7772-4045-b045-2cca7ca675d4)
- 주변의 교통시설 여부에 따라 집값에 영향이 있을 것이라는 가설
- 외부 버스 데이터와 위도,경도 값을 이용 각, 데이터마다 일정 거리 이내에 버스 정류장이 몇 개가 있는지를 기준으로 버스 정류장의 총합을 계산한 피처 생성
- ‘역세권'의 기준이 500m 이내에 지하철역이 있는가 이므로 버스 정류장의 개수를 세는 기준도 500m 단위로 설정

#### < 가장 가까운 학교와의 거리 feature >
![스크린샷 2024-01-25 오후 4 20 33](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/c200c07f-a317-4049-a752-565ab0b08942)

- 아파트에 가까운 학교(초,중,고)가 있다면  아파트거래가격에 영향을 줄 것이라 가정
- 따라서 초,중,고등학교에 구분 없이 가장 가까운 학교와의 거리 피처를 생성
- 공공데이터의 학교 별 위도, 경도 데이터와 아파트의 위도, 경도 데이터를 harversine distance로 계산하여dist_to_nearest_school에 저장

#### < 이전가격 feature >
![스크린샷 2024-01-25 오후 4 02 45](https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/d9e0968f-c90c-4ff0-9add-1d8e985b4353)

- 장기로는 다른 요인의 영향을 많이 받겠지만, 단기로는 직전 시세가 가장 중요
- 결국 우리가 학습하려는 데이터는 최근 3년간 데이터만 학습하기로 했기 때문에 동일 아파트, 동일 면적에 대한 직전 거래 가격을 이전 가격으로 추가
- 해당 이전 가격과 target간의 상관관계는 0.98로 매우 높았습니다.
- 특히, 고가 아파트의 경우에는 저가 아파트와 다르게 비슷한 특성이 없기 때문에 해당 컬럼을 이용하는게 매우 주요했습니다.
  
## 4. Modeling

#### Train-Validation Split

> 부동산 데이터는 자산 가격 특성상 외부적 요인에 영향을 매우 많이 받을 가능성이 높습니다.
실제로 대통령이 누구인지에 따라서도 가격 상승에 차이가 많이 납니다.
하지만 이런 비정형 데이터(자산 상승 호재, 재건축 찌라시)를 약 20년간에 걸쳐 찾거나 정의하는 것은 어렵습니다.
따라서 최신의 데이터를 잘 맞추는 모델로 진행해보자라는 결론을 도출했습니다.

- Train-valid를 random split으로 하는것이 아니라 2023년 4~6월을 validation으로 선정하고, 이전 데이터를 Train dataset으로 지정했습니다.
- 또한, 학습 자체도 3년 이내의 부동산 데이터만 활용해서, 시기적 특성요소를 최대한 덜 학습하도록 했습니다.
- 진행하는 과정에서 Validation RMSE와 리더보드 RMSE 결과가 비례하지 않아 2023년 1월 ~ 3월을 Valid로, 2023년 4월 ~ 6월은 test 데이터셋으로 구축해서 모델간에 비교를 진행해서 최우수 모델로 선정했습니다.

#### 가격대별 별도 모델 구축

> RMSE가 8만 ~ 10만 정도로 나오는데 이렇게나 지표가 높게 나타난다는 것은 결국 비싼 아파트를 싸게 예측하는 경우밖에 없다고 판단했습니다.
실제로 valid data에서 예측을 잘 못하는 모델을 보아도 90억짜리 아파트를 28억으로 예측하는 것을 볼 수 있습니다.


- 따라서 최종 모델은 30억 이상 고가 아파트를 예측하는 모델과 그 이하 가격대의 아파트를 예측하는 모델을 분리하고 답을 합치는 형태로 진행했습니다.
- 30억 이상 고가라는 것을 테스트 데이터에서는 확인할 수 없기 때문에 2020.01~2023.06 동안 30억 이상으로 거래된 아파트들을 모두 가져와서 트레이닝 데이터셋으로 구축했고, 테스트 데이터셋에서는 이 아파트명을 가진 index만 예측했습니다.
- 실제 프로덕션에서 이 모델을 활용하기 위해서는 별도로 고가 아파트라는 데이터셋을 구축해야한다는 한계가 있습니다.

#### 저가 아파트 모델링 : 30억 미만
- target 300,000 미만 데이터 사용
  - 학습 데이터 : 2020년 01월 ~ 2022년 12월
  - 검증 데이터 : 2023년 01월 ~ 2023년 03월
  - 평가 데이터 : 2023년 04월 ~ 2023년 06월 
- 모델 : LightGBM
- Hyper-Parameter tuning : Optuna

- LightGBM 하이퍼파라미터 튜닝 전
  - Train Score : 11129.8078
  - Valid Score : 13101.2657
  - Test Score : 14701.9578

- LightGBM optuna 하이퍼파라미터 튜닝 후
  - Train Score : 4412.8290
  - Valid Score : 9704.2133
  - Test Score : 12333.9627
- 최종 학습 및 2023.04~2023.06 최종 테스트
  - Test Score : 10015.5281

#### 고가 아파트 모델링 : 30억 이상
- target 300,000 이상 데이터 사용
  - 학습 데이터 : 2020년 01월 ~ 2022년 12월
  - 검증 데이터 : 2023년 01월 ~ 2023년 03월
  - 평가 데이터 : 2023년 04월 ~ 2023년 06월 
  - 모델 : LightGBM
- 사용 변수
  - '꼭대기층 여부', '이전가격', '전용면적', '아파트 평균높이', '연GDP', '층', '계약년월', 'y', '한강거리', '500m이내 정류장 수','건물나이'
- 최종 학습 및 2023.04~2023.06 최종 테스트
  - num_estimators 수 : 410개
  - Test Score : 30572.5281

#### 최종 제출 모델
- 저가 아파트 모델 예측값 & 고가 아파트 모델 예측값
- 저가 아파트 데이터 : 2020년 01월 ~ 2023년 03월
- 고가 아파트 데이터 : 2023년 01월 ~ 2023년 06월
- 평가 데이터 : 2023년 07월 ~ 2023년 09월 
- 모델 : LightGBM
- Hyper-Parameter tuning : WandB

> <저가 아파트 모델>
- Train RMSE : 4958.61
- Valid RMSE : 9761.01

> <고가 아파트 모델>
- Train RMSE :  5493.75
- Valid RMSE :  26855.08

> <Public 결과>
- Public RMSE : 104262.6919

> <Private 결과>
- Private RMSE : 86148.2275

## 5. Result

### Leader Board

#### Private LB
<img width="1094" alt="스크린샷 2024-01-25 오후 7 38 09" src="https://github.com/UpstageAILab/upstage-ml-regression-07/assets/46295610/8c5a662b-bc08-40e2-8204-2081150386da">


### Presentation
[패스트캠퍼스X업스테이지 AI Lab_집값 예측 대회 ML 7조.pdf](https://github.com/UpstageAILab/upstage-ml-regression-07/files/14059434/X.AI.Lab_.ML.7.pdf)


## etc

### Meeting Log
- Notion
  
  https://www.notion.so/7-9bf356d1cd69404681bd4a0ba7453c77

- 대회 마지막 주는 Zoom 실시간 미팅(10:00am ~ 19:00pm)   

### Reference
- Kaggle House Prices - Advanced Regression Techniques

  https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques
  
- Kaggle Handbook: Tips & Tricks To Survive a Kaggle Shake-up
  
  https://medium.com/global-maksimum-data-information-technologies/kaggle-handbook-tips-tricks-to-survive-a-kaggle-shake-up-23675beed05e

- Dacon Code Share :  아파트 실거래가 예측 대회
  
  https://dacon.io/competitions/official/21265/codeshare/439?page=1&dtype=recent

- 건축물 대장 Data
  
  https://openab.seoul.go.kr/build/info.do?gubun=document

- 시군구별 근로소득 Data

  https://kosis.kr/statHtml/statHtml.do?tblId=DT_133001N_4215&orgId=133&language=kor&conn_path=&vw_cd=&list_id

- 매매수급동향 Data

  https://www.data.go.kr/data/15044273/fileData.do

- 서울시 연도별 GDP Data

  https://data.seoul.go.kr/dataList/91/S/2/datasetView.do

- 기준금리 Data

  https://www.bok.or.kr/portal/singl/baseRate/list.do?dataSeCd=01&menuNo=200643

- 소비자물가지수 Data

  https://www.index.go.kr/unify/idx-info.do?idxCd=4226
