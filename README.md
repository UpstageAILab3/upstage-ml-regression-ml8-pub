[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D1pZhJxu)
# Title (Please modify the title)

## Team

| ![전승열](https://avatars.githubusercontent.com/u/156163982?v=4) | ![조재현](https://avatars.githubusercontent.com/u/156163982?v=4) | ![최제우](https://avatars.githubusercontent.com/u/156163982?v=4) | ![장재성](https://avatars.githubusercontent.com/u/156163982?v=4) | ![정환희](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [전승열](https://github.com/delightflow)             |            [조재현](https://github.com/jojaen)             |            [최제우](https://github.com/JeWoo-Choi)             |            [장재성](https://github.com/mirrbandi)             |            [정환희](https://github.com/ManfMars)             |
|                            팀장, 코딩                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |

## 1. Competiton Info

### Overview

## 경진대회 주제
House Price Prediction 경진대회는 주어진 데이터를 활용하여 서울의 아파트 실거래가를 효과적으로 예측하는 모델을 개발하는 대회입니다. 

부동산은 의식주에서의 주로 중요한 요소 중 하나입니다. 이러한 부동산은 아파트 자체의 가치도 중요하고, 주변 요소 (강, 공원, 백화점 등)에 의해서도 영향을 받아 시간에 따라 가격이 많이 변동합니다. 개인에 입장에서는 더 싼 가격에 좋은 집을 찾고 싶고, 판매자의 입장에서는 적절한 가격에 집을 판매하기를 원합니다. 부동산 실거래가의 예측은 이러한 시세를 예측하여 적정한 가격에 구매와 판매를 도와주게 합니다. 그리고, 정부의 입장에서는 비정상적으로 시세가 이상한 부분을 체크하여 이상 신호를 파악하거나, 업거래 다운거래 등 부정한 거래를 하는 사람들을 잡아낼 수도 있습니다. 

저희는 이러한 목적 하에서 다양한 부동산 관련 의사결정을 돕고자 하는 부동산 실거래가를 예측하는 모델을 개발하는 것입니다. 특히, 가장 중요한 서울시로 한정해서 서울시의 아파트 가격을 예측하려고합니다.

![image](https://github.com/user-attachments/assets/027c5a90-3d09-4a8c-9dfe-475fde2292d6)


참가자들은 대회에서 제공된 데이터셋을 기반으로 모델을 학습하고, 서울시 각 지역의 아파트 매매 실거래가를 예측하는데 중점을 둡니다. 이를 위해 선형 회귀, 결정 트리, 랜덤 포레스트, 혹은 딥 러닝과 같은 다양한 regression 알고리즘을 사용할 수 있습니다.


제공되는 데이터셋은 총 네가지입니다. 첫번째는 국토교통부에서 제공하는 아파트 실거래가 데이터로 아파트의 위치, 크기, 건축 연도, 주변 시설 및 교통 편의성과 같은 다양한 특징들을 포함하고 있습니다. 두번째와 세번째 데이터는 추가 데이터로, 서울시에서 제공하는 지하철역과 버스정류장에 대한 다양한 정보들을 포함하고 있습니다. 마지막 네번째 데이터는 평가 데이터로, 최종 모델성능에 대한 검증을 위해 사용됩니다.

참가자들은 이러한 다양한 변수와 데이터를 고려하여 모델을 훈련하고, 아파트의 실거래가에 대한 예측 성능을 높이기 위한 최적의 방법을 찾아야 합니다.

![image](https://github.com/user-attachments/assets/f269b341-c711-4377-b4c5-07f7ad4048ef)


경진대회의 목표는 정확하고 일반화된 모델을 개발하여 아파트 시장의 동향을 미리 예측하는 것입니다. 이를 통해 부동산 관련 의사 결정을 돕고, 효율적인 거래를 촉진할 수 있습니다. 또한, 참가자들은 모델의 성능을 평가하고 다양한 특성 간의 상관 관계를 심층적으로 이해함으로써 데이터 과학과 머신 러닝 분야에서의 실전 경험을 쌓을 수 있습니다.

input : 9,272개의 아파트 특징 및 거래정보

output : 9,272개의 input에 대한 예상 아파트 거래금액

- 경진대회 구현 내용, 컨셉, 교육 내용과의 관련성 등


**구현 내용**

- 데이터 수집: 서울시 아파트 실거래가 데이터를 수집하여 전처리합니다.
- 데이터 분석: 다양한 분석 기법을 통해 데이터를 탐색하고, 가격에 영향을 미치는 주요 요인을 파악합니다.
- 모델 개발: 회귀분석, 랜덤 포레스트, XGBoost 등 다양한 머신러닝 알고리즘을 활용하여 예측 모델을 개발합니다.
- 모델 평가: RMSE, MAE 등의 지표를 사용하여 모델의 성능을 평가합니다.
- 모델 최적화: 하이퍼파라미터 튜닝, 교차 검증 등을 통해 모델을 최적화합니다.

**컨셉**:

- 부동산 가격 예측을 통해 개인과 판매자가 합리적인 의사결정을 할 수 있도록 돕고, 정부가 부정 거래를 감지할 수 있도록 지원합니다.
- 데이터 기반의 접근 방식을 통해 부동산 시장의 투명성과 효율성을 높입니다.

**교육 내용과의 관련성**:

- 데이터 사이언스: 데이터 전처리, 탐색적 데이터 분석, 머신러닝 모델링 등 데이터 사이언스의 핵심 개념을 활용합니다.
- 경제학: 부동산 시장의 동향과 가격 결정 요인에 대한 이해를 바탕으로 모델링을 수행합니다.
- 컴퓨터 공학: 프로그래밍, 데이터베이스, 소프트웨어 개발 등 컴퓨터 공학의 기술을 적용합니다.

**개발 환경**:

- 프로그래밍 언어: Python
- 개발 도구: Jupyter Notebook, PyCharm, Visual Studio Code 등
- 라이브러리: pandas, numpy, scikit-learn, XGBoost, LightGBM 등

**협업 도구**:

- 버전 관리: Git, GitHub
- 프로젝트 관리: Trello, Asana
- 커뮤니케이션: Slack, Zoom

**데이터셋**: 서울시 아파트 실거래가 데이터
    - **컬럼**:
        - `date`: 거래 날짜
        - `apartment_name`: 아파트 이름
        - `location`: 위치 (구, 동 등)
        - `size`: 전용 면적 (m²)
        - `floor`: 층수
        - `price`: 거래 가격 (원)
        - `nearby_amenities`: 주변 시설 (예: 강, 공원, 백화점 등)
        - `transportation`: 교통 (지하철역 거리 등)
    - **연관도**:
        - `location`과 `price`: 위치는 가격에 큰 영향을 미침
        - `size`와 `price`: 면적이 클수록 가격이 높아지는 경향
        - `nearby_amenities`와 `price`: 주변 시설이 많을수록 가격이 높아짐
        - `transportation`과 `price`: 교통 접근성이 좋을수록 가격이 높아짐
  

### Timeline
24년 7월 9일 ~ 7월 19일

### Evaluation

- _Write how to evaluate model_

## 2. Components

### Directory

[예시자료]
project-root/
├── data/
│   ├── raw/
│   │   └── seoul_apartment_prices.csv
│   ├── processed/
│   │   └── processed_data.csv
│   └── external/
│       └── additional_data.csv
├── notebooks/
│   ├── EDA.ipynb
│   ├── preprocessing.ipynb
│   ├── model_development.ipynb
│   ├── model_evaluation.ipynb
│   └── feature_engineering.ipynb
├── models/
│   ├── linear_regression.pkl
│   ├── random_forest.pkl
│   ├── xgboost.pkl
│   └── lightgbm.pkl
├── reports/
│   ├── figures/
│   │   └── feature_importance.png
│   └── final_report.pdf
├── src/
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── model_training.py
│   └── model_evaluation.py
├── requirements.txt
└── README.md


## 3. Data descrption

### Dataset overview

- _Explain using data_

### EDA
탐색적 데이터 분석은 학습 데이터의 특성을 이해하고, 중요한 패턴과 상관관계를 발견하는 데 중점을 둡니다.



- **데이터 로드 및 개요 확인**:
    - 데이터셋의 기본 통계값(평균, 표준편차, 최소/최대값 등)을 확인합니다.
    - 결측치 및 이상치를 확인하고 처리합니다.
!['결측치 비율'](https://ifh.cc/g/TMMtbY.png)
!['상관계수'](https://ifh.cc/g/vc8Rbg.jpg)
!['전용면적 별 평균 부동산 거래액 비교'](https://ifh.cc/g/kD6pmb.png)
!['건축연도 분포'](https://ifh.cc/g/kpRmVa.png)
!['구매연식'](https://ifh.cc/g/n3PV5n.png)
!['거래건수 상위 10개 구'](https://ifh.cc/g/hJhl0n.png)
!['거래건수 상위 10개 구 평균 가'](https://ifh.cc/g/ZAGZ2x.png)
[결과 값 내용]

- **데이터 시각화**:
    - `price`의 분포를 확인하여 데이터의 분포 특성을 파악합니다.
     !['부동산 가격 분포'](https://ifh.cc/g/8VlANQ.png)
    - `location`에 따른 `price`의 차이를 확인하기 위해, 지역별 평균 가격을 시각화합니다.
     !['구별 평균 가격'](https://ifh.cc/g/q76fyg.png)
    - `size`와 `price`의 관계를 산점도로 시각화하여 면적과 가격의 상관관계를 분석합니다.
    - `nearby_amenities`와 `price`의 관계를 시각화하여 주변 시설이 가격에 미치는 영향을 분석합니다.
    - `transportation` 접근성(예: 지하철역 거리)과 `price`의 관계를 시각화하여 교통 편의성이 가격에 미치는 영향을 분석합니다.

[시각화 내용 기입]
- _Describe your EDA process and step-by-step conclusion_

### Feature engineering

**데이터 전처리**:

- **결측치 처리**:
    - 결측치가 있는 컬럼에 대해 평균값, 중간값, 또는 최빈값으로 대체하거나, 필요에 따라 결측치가 있는 행을 제거합니다.

[결측치 처리 내용]

- **이상치 처리**:
    - 이상치를 식별하고, 필요에 따라 제거하거나 변환합니다.

[이상치 처리 내용]

- **특성 변환 및 엔지니어링**:
    - 날짜 정보를 연도, 월 등의 세부적인 시간 요소로 변환합니다.
    - 카테고리형 변수(예: `location`)를 원-핫 인코딩(One-Hot Encoding)으로 변환합니다.
    - 새로운 특성(예: `price_per_sqm`)을 생성하여 모델의 성능을 향상시킵니다.

- **데이터 스케일링**:
    - 모델에 따라 필요시, Min-Max 스케일링 또는 표준화(Standardization)를 적용합니다.

- _Describe feature engineering process_

## 4. Modeling

### Model descrition
[모델링 자료 첨부 필요]
- _Write model information and why your select this model_

### Modeling Process

**모델링 접근 방식**:
부동산 가격 예측 문제는 회귀 문제로 접근합니다. 다양한 머신러닝 알고리즘을 사용하여 최적의 예측 모델을 개발합니다. 주요 알고리즘은 다음과 같습니다.

1. **선형 회귀 (Linear Regression)**:
    - 단순하지만 해석이 용이한 기본 회귀 모델입니다.
    - 가격과 각 특성 간의 선형 관계를 가정합니다.
2. **랜덤 포레스트 회귀 (Random Forest Regression)**:
    - 여러 개의 결정 트리를 앙상블하여 예측 성능을 향상시킵니다.
    - 특성의 중요도를 계산하여 중요한 요인을 파악할 수 있습니다.
3. **XGBoost**:
    - 부스팅 기법을 사용하여 예측 성능을 극대화합니다.
    - 빠른 학습 속도와 높은 예측 정확도를 제공합니다.
4. **LightGBM**:
    - XGBoost와 유사한 부스팅 기법을 사용하지만, 더 빠르고 메모리 효율적입니다.
    - 대규모 데이터셋에 적합합니다.
      
- _Write model train and test process with capture_

## 5. Result

[결과치 및 리더보드 내용 작성 필요]
### Leader Board

- _Insert Leader Board Capture_
- _Write rank and score_

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

### Reference
