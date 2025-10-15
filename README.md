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
- 📝 주제: MNIST · Fashion-MNIST · CIFAR-10 데이터셋을 활용한 딥러닝 분류 실습  
- 📊 데이터셋: MNIST (붓글씨 숫자), Fashion-MNIST (의류 이미지), CIFAR-10 (컬러 이미지 데이터)  
- 📂 주요 파일:
- `week7/MNIST_CNN.ipynb`
- MNIST 데이터셋으로 **CNN 기반 분류 모델 구현**  
- `Conv2D → MaxPooling2D → Flatten → Dense` 구조  
- 테스트 정확도 및 혼동행렬 출력  

#### 👕 `week7/MNIST_fashion_DNN.ipynb`
- **Fashion-MNIST 데이터셋**으로 DNN(완전연결 신경망) 분류  
- `Flatten → Dense(256, 128) → Dropout → Softmax` 구조  
- 모델 정확도 및 분류 리포트 출력  

#### 👗 `week7/MNIST_fashion_CNN.ipynb`
- **Fashion-MNIST 데이터셋**으로 CNN 기반 분류 모델 구현  
- `Conv2D → MaxPooling2D → Dropout → Dense` 구조  
- 테스트 정확도, 분류 리포트, 혼동행렬 시각화 포함  

#### 🐶 `week7/CIFAR-10_CNN.ipynb`
- **CIFAR-10 데이터셋** 중 `cat`, `dog`, `horse` 3개 클래스만 선택하여 분류  
- 간단한 데이터 증강(`RandomFlip`, `RandomRotation`) 포함  
- `Conv2D → MaxPooling2D → Flatten → Dense` 구조, 3-class Softmax 출력  
- Classification Report 및 Confusion Matrix로 성능 평가  

---

### ✅ 학습 목표
- CNN/DNN 구조를 직접 구현하며 이미지 분류의 기본 원리 이해  
- 데이터 정규화 및 채널 차원 개념 숙지  
- Dropout, BatchNormalization, 데이터 증강 등을 통한 과적합 방지 경험  
- 분류 리포트(Classification Report)와 혼동행렬(Confusion Matrix)을 통해 성능 분석
