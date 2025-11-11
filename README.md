# Machine Learning Programming Lab 👩🏻‍💻

기계학습프로그래밍(2) 수업의 주차별 실습 코드와 데이터셋을 정리한 저장소입니다.  
본 저장소는 **Google Colab** 기반의 코드와 실습 자료를 포함하고 있습니다.

<br>

## 🗂 Week 2
- 📝 주제: 대표적인 머신러닝 데이터셋 실습  
- 📊 데이터셋: Boston, Breast Cancer, Car Evaluation, Diabetes, Iris  
- 📂 주요 파일:
	- `week2/boston.ipynb`
    - `week2/breast_cancer.ipynb`
    - `week2/car_evaluation.ipynb`
    - `week2/diabetes.ipynb`
 	- `week2/iris.ipynb`


## 🗂 Week 3
- 📝 주제: 머신러닝 분류(Classification)와 회귀(Regression) 실습  
- 📊 데이터셋: Raisin, Weather  
- 📂 주요 파일:  
  - `week3/Raisin.ipynb`  
  - `week3/weather_classfication.ipynb`  
  - `week3/weather_regression.ipynb`


## 🗂 Week 4
- 📝 주제: 화이트 와인 / 유방암 데이터셋을 활용한 머신러닝 & 딥러닝 분류 실습  
- 📊 데이터셋: Wine Quality (White), Breast Cancer  
- 📂 주요 파일:  
  - `week4/ML_winequality_white.ipynb`  
    - 화이트 와인 데이터셋으로 **4가지 머신러닝 분류**
    - 로지스틱 회귀의 기울기(Coefficients) & 절편(Intercept) 출력  
  - `week4/DL_winequality_white.ipynb`  
    - 화이트 와인 데이터셋으로 **딥러닝 분류**  (Fully Connected Layer만 사용)  
  - `week4/DL_breast_cancer.ipynb`  
    - 유방암 데이터셋으로 **딥러닝 분류**  (Fully Connected Layer만 사용)
    - ⭐️ 'softmax' -> 'sigmoid' 로 수정
    - ⭐️ 'categorical_crossentropy' -> 'binary_crossentropy' 로 수정


## 🗂 Week 5
- 📝 주제: 필기체 숫자 / 당뇨병 데이터셋을 활용한 머신러닝 & 딥러닝 분류·회귀 실습  
- 📊 데이터셋: Digits, Diabetes  
- 📂 주요 파일:  
  - `week5/ML_digits.ipynb`  
    - Digits 데이터셋으로 **3가지 머신러닝 분류**  
    - Decision Tree, Logistic Regression, Random Forest 비교  
  - `week5/DL_digits.ipynb`  
    - Digits 데이터셋으로 **딥러닝 분류 (MLP)**  
    - Fully Connected Layer 기반, Dropout 포함  
  - `week5/DL_diabetes.ipynb`  
    - Diabetes 데이터셋으로 **딥러닝 회귀 (BMI 예측)**  
    - Fully Connected Layer 기반, Dropout 포함
   

## 🗂 Week 7
- 📝 주제: Fashion-MNIST / MNIST / CIFAR-10 데이터셋을 활용한 딥러닝 분류 실습  
- 📊 데이터셋: Fashion-MNIST (의류 이미지), MNIST (붓글씨 숫자), CIFAR-10 (컬러 이미지 데이터)  
- 📂 주요 파일:
  - `week7/MNIST_fashion_DNN.ipynb`
	- Fashion-MNIST 데이터셋로 **DNN 기반 분류** 
	- Flatten → Dense → Dropout → Softmax 구조  
	- 평가 지표 출력
  - `week7/MNIST_fashion_CNN.ipynb`
	- Fashion-MNIST 데이터셋으로 **CNN 기반 분류** 
	- Conv2D → MaxPooling2D → Flatten → Dropout → Dense → Softmax 구조  
	- 평가 지표 출력
  - `week7/MNIST_CNN.ipynb`
	- MNIST 데이터셋으로 **CNN 기반 분류**
	- Conv2D → MaxPooling2D → Flatten → Dropout → Dense → Softmax 구조
	- 평가 지표 출력
  - `week7/CIFAR-10_CNN.ipynb`
	- CIFAR-10 데이터셋 중 'cat', 'dog', 'horse' 3개 클래스만 선택하여 **CNN 기반 분류** 
	- Conv2D → MaxPooling2D → Flatten → Dropout → Dense → Softmax 구조
	- 평가 지표 출력


## 🗂 Week 9
- 📝 주제: 시계열 데이터 예측 (RNN / LSTM 기반 시계열 분석 실습) 
- 📊 데이터셋: Alcohol_Sales (미국 주류 판매량 월별 데이터), TSLA (테슬라 주가 일별 종가 데이터)
- 📂 주요 파일:
  - `week9/AlcoholSales_RNN_LSTM.ipynb`
    - Alcohol_Sales 데이터셋을 활용하여 최근 12개월 데이터로 **다음 달 판매량 예측**
	- RNN(SimpleRNN) / LSTM 비교  
	- 각 모델별 Train/Test MSE 출력
    - 예측 결과 및 그래프 시각화
  - `week9/TSLA_RNN_LSTM.ipynb`
    - TSLA 데이터셋을 활용하여 최근 60일 종가로 **다음날 종가를 예측**
	- RNN(SimpleRNN) / LSTM 비교  
	- 각 모델별 Train/Test MSE 출력
    - 예측 결과 및 그래프 시각화


## 🗂 Week 10
- 📝 주제: 인체 활동 인식 (Human Activity Recognition) — 1D 시계열 분류  
- 📊 데이터셋: UCI HAR Dataset (UCI Human Activity Recognition Using Smartphones)   
- 📂 주요 파일:  
  - `week10/UCI_HAR_SimpleCNN.ipynb`  
    - StandardScaler 적용  
    - 모델 구성: **Simple CNN**
    - 평가 지표 출력
  - `week10/UCI_HAR_LSTM.ipynb`  
    - StandardScaler 적용 
    - 모델 구성: **LSTM**
    - 평가 지표 출력
  - `week10/UCI_HAR_GRU.ipynb`  
    - StandardScaler 적용 
    - 모델 구성: **GRU**
    - 평가 지표 출력
  - `week10/UCI_HAR_CNN_LSTM.ipynb`  
    - StandardScaler 적용  
    - 모델 구성: **CNN+LSTM**
    - 평가 지표 출력
  - `week10/UCI_HAR_CNN_GRU.ipynb`  
    - StandardScaler 적용 
    - 모델 구성: **CNN+GRU**
    - 평가 지표 출력

## 🗂 Week 11
- 📝 주제: 이상 거래 탐지 (Creditcard) & 행동 인식 (WISDM)
- 📊 데이터셋:
 	- Creditcard (신용카드 사기 거래 탐지용 데이터)-*파일 용량이 커서 GitHub 업로드 제외*,
    - WISDM (스마트폰/워치 센서 기반 인간 행동 인식 데이터)
- 📂 주요 파일:
  - `week11/creditcard.ipynb`
	- creditcard.csv 데이터를 활용한 AutoEncoder 기반 이상 거래 탐지
	- 정상 거래(0) 데이터만으로 학습하여 재구성 오차(Reconstruction Error) 기반으로 사기 거래(1) 판별
	- 혼동 행렬 및 classification_report 출력
  - `week11/WISDM.ipynb`
	- WISDM.csv 데이터를 활용한 행동 인식 이진 분류 (Jogging vs Sitting)
	- AutoEncoder 기반 비지도 학습 모델로 정상(조깅) 데이터를 학습하고, 비정상(앉기) 데이터를 재구성 오차로 탐지
	- 데이터 전처리
    - 혼동 행렬 및 classification_report 출력
