[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D1pZhJxu)
# House Price Prediction | 아파트 실거래가 예측

## Team

| ![박건민](https://avatars.githubusercontent.com/u/156163982?v=4) | ![박범철](https://avatars.githubusercontent.com/u/156163982?v=4) | ![임동건](https://avatars.githubusercontent.com/u/156163982?v=4) | ![임종현](https://avatars.githubusercontent.com/u/156163982?v=4) | ![홍진영](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [임동건](https://github.com/UpstageAILab)             |            [박건민](https://github.com/UpstageAILab)             |            [박범철](https://github.com/UpstageAILab)             |            [홍진영](https://github.com/Jeandeluge)             |            [임종현](https://github.com/UpstageAILab)             |
|                            팀장, 피처 엔지니어링                             |                           데이터 전처리                             |                            모델링                             |                            EDA                             |                            담당 역할                             |

## 1. Competiton Info

### Overview

House Price Prediction 경진대회는 주어진 데이터를 활용하여 서울의 아파트 실거래가를 효과적으로 예측하는 모델을 개발하는 대회입니다. 

부동산은 의식주에서의 주로 중요한 요소 중 하나입니다. 이러한 부동산은 아파트 자체의 가치도 중요하고, 주변 요소 (강, 공원, 백화점 등)에 의해서도 영향을 받아 시간에 따라 가격이 많이 변동합니다. 개인에 입장에서는 더 싼 가격에 좋은 집을 찾고 싶고, 판매자의 입장에서는 적절한 가격에 집을 판매하기를 원합니다. 부동산 실거래가의 예측은 이러한 시세를 예측하여 적정한 가격에 구매와 판매를 도와주게 합니다. 그리고, 정부의 입장에서는 비정상적으로 시세가 이상한 부분을 체크하여 이상 신호를 파악하거나, 업거래 다운거래 등 부정한 거래를 하는 사람들을 잡아낼 수도 있습니다. 

저희는 이러한 목적 하에서 다양한 부동산 관련 의사결정을 돕고자 하는 부동산 실거래가를 예측하는 모델을 개발하는 것입니다. 특히, 가장 중요한 서울시로 한정해서 서울시의 아파트 가격을 예측하려고합니다.

<p align="center">
  <img src="https://lh3.googleusercontent.com/roapcb2K4QL9_giBxUh4fOBODWS20U_4U-OXEDsqz9_T0T48FvQ04zJA7e8674Lfu_A2-MC5cM3N1tYTTB4pOgvXlglLenp7M-Q2sLjtqVlZgdBn2dEX_2TU4W5PRqj6OanV1vTriAjarvV9EbVOsYQ">
</p>

참가자들은 대회에서 제공된 데이터셋을 기반으로 모델을 학습하고, 서울시 각 지역의 아파트 매매 실거래가를 예측하는데 중점을 둡니다. 이를 위해 선형 회귀, 결정 트리, 랜덤 포레스트, 혹은 딥 러닝과 같은 다양한 regression 알고리즘을 사용할 수 있습니다.


제공되는 데이터셋은 총 네가지입니다. 첫번째는 국토교통부에서 제공하는 아파트 실거래가 데이터로 아파트의 위치, 크기, 건축 연도, 주변 시설 및 교통 편의성과 같은 다양한 특징들을 포함하고 있습니다. 두번째와 세번째 데이터는 추가 데이터로, 서울시에서 제공하는 지하철역과 버스정류장에 대한 다양한 정보들을 포함하고 있습니다. 마지막 네번째 데이터는 평가 데이터로, 최종 모델성능에 대한 검증을 위해 사용됩니다.

참가자들은 이러한 다양한 변수와 데이터를 고려하여 모델을 훈련하고, 아파트의 실거래가에 대한 예측 성능을 높이기 위한 최적의 방법을 찾아야 합니다.

<p align="center">
  <img src="https://lh6.googleusercontent.com/C5zIYzypbQHFcvdiaQV4u6cRZDRyRA1EL6R2Ca3l-CkMnyK7jSM_BSAXZXyH65U0F8nSxx9XYJ9rsX1jo-r_ICEMzHhNrvuoJ7vHG1YGRZORSQ_QZh72sgLyiFPIuyUi2mSIdQtEkIvvFGpL8WFW1y8">
</p>

경진대회의 목표는 정확하고 일반화된 모델을 개발하여 아파트 시장의 동향을 미리 예측하는 것입니다. 이를 통해 부동산 관련 의사 결정을 돕고, 효율적인 거래를 촉진할 수 있습니다. 또한, 참가자들은 모델의 성능을 평가하고 다양한 특성 간의 상관 관계를 심층적으로 이해함으로써 데이터 과학과 머신 러닝 분야에서의 실전 경험을 쌓을 수 있습니다.

본 대회는 결과물 csv 확장자 파일을 제출하게 됩니다.

- input : 9,272개의 아파트 특징 및 거래정보

- output : 9,272개의 input에 대한 예상 아파트 거래금액

### Timeline

- ex) January 10, 2024 - Start Date
- ex) February 10, 2024 - Final submission deadline

### Evaluation

해당 시점의 매매 실거래가를 예측하는 Regression 대회이며, 평가지표는 RMSE(Root Mean Squared Error)를 사용합니다.

<p align="center">
  <img src="https://lh6.googleusercontent.com/cKB-Cb275gGnl_wFKTnUGB3qLDn-q8fo6phdX_sgPoQSKj2MjE2kOPjC3qE39B2NDkhEWOUQ5LPttHsl4fQiKUyhYXTvFh1A33Ru1dXgIF1NYr-eVvR_AdJlqVwEfCNcXt5W3874k_16TByJDIm3z5E">
</p>

RMSE는 예측된 값과 실제 값 간의 평균편차를 측정합니다. 아파트 매매의 맥락에서는 회귀 모델이 실제 거래 가격의 차이를 얼마나 잘 잡아내는지 측정합니다. 

## 2. Components

### Directory

- _Insert your directory structure_

## 3. Data descrption

### Dataset overview

- _Explain using data_

### EDA

- _Describe your EDA process and step-by-step conclusion_

### Feature engineering

- _Describe feature engineering process_

## 4. Modeling

### Model Description

모델링에서는 처음에 시계열 모델을 활용하여 진행하였습니다. 시계열 데이터의 특성을 잘 반영할 수 있는 다양한 모델들을 실험한 결과, RandomForest와 CatBoost 모델이 가장 좋은 성능을 보였습니다. 각각의 모델은 다음과 같은 이유로 선택되었습니다:

- **RandomForest:** 여러 결정 트리의 앙상블을 통해 과적합을 방지하고, 데이터의 다양한 패턴을 학습할 수 있어 예측 성능이 뛰어납니다.
- **CatBoost:** 범주형 변수 처리가 우수하고, 과적합을 방지하는 강력한 성능을 제공하여 복잡한 데이터에서도 높은 예측 정확도를 보장합니다.

### Modeling Process

모델링 과정은 아래와 같은 단계로 진행되었습니다:

1. **다양한 시계열 모델 실행**
   - ARIMA, SARIMA, LSTM 등 여러 시계열 모델을 실행하여 성능을 비교했습니다.

2. **가장 좋은 점수를 내는 모델 확인**
   - RandomForest와 CatBoost 모델이 다른 모델들에 비해 가장 좋은 성능을 보였습니다.

3. **RandomForest 모델 파라미터 수정**
   - Grid Search 및 Random Search를 사용하여 RandomForest 모델의 하이퍼파라미터를 최적화했습니다.

4. **CatBoost 모델 파라미터 수정**
   - CatBoost의 하이퍼파라미터도 최적화하기 위해 Grid Search 및 Random Search를 활용했습니다.

5. **RandomForest, CatBoost 앙상블 진행**
   - 두 모델의 예측 결과를 결합하여 앙상블 모델을 구축했습니다.

6. **앙상블 모델 비율 설정**
   - 최종 앙상블 모델의 비율을 조정하여 가장 높은 예측 성능을 달성했습니다.


## 5. Result

### Leader Board
<img width="804" alt="스크린샷 2024-07-22 오후 12 42 01" src="https://github.com/user-attachments/assets/192882af-9f0f-4bf6-8175-184de421ada7">


### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_
