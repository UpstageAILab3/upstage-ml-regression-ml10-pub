[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/D1pZhJxu)
# House Price Prediction | 아파트 실거래가 예측

## Team

| ![박건민](https://avatars.githubusercontent.com/u/156163982?v=4) | ![박범철](https://avatars.githubusercontent.com/u/156163982?v=4) | ![임동건](https://avatars.githubusercontent.com/u/156163982?v=4) | ![임종현](https://avatars.githubusercontent.com/u/156163982?v=4) | ![홍진영](https://avatars.githubusercontent.com/u/156163982?v=4) |
| :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: | :--------------------------------------------------------------: |
|            [임동건](https://github.com/UpstageAILab)             |            [박건민](https://github.com/UpstageAILab)             |            [박범철](https://github.com/UpstageAILab)             |            [홍진영](https://github.com/Jeandeluge)             |            [임종현](https://github.com/UpstageAILab)             |
|                            팀장, 담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |                            담당 역할                             |

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

### Model descrition

- _Write model information and why your select this model_

### Modeling Process

- _Write model train and test process with capture_

## 5. Result

### Leader Board

- _Insert Leader Board Capture_
- _Write rank and score_

### Presentation

- _Insert your presentaion file(pdf) link_

## etc

### Meeting Log

- _Insert your meeting log link like Notion or Google Docs_

### Reference

- _Insert related reference_
