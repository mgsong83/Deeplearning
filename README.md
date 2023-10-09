# Deeplearning

Deep learning lecture matriels
삼성전자 설비연 내부 스터디 - 딥러닝 강의용 교재


made by msong. 
last updated  2023. 09. 


---- 


사용환경 (miniconda) 설치권장

Apple silicon Mac OS (M2) 와 원도우10, 그리고 Ubuntu 20.04 LTS 버전에서 동작이 확인되었습니다.

- python 3.X 
- pytorch 2.X
- tensorflow 2.X
- torch lighting 2.X 




----

## 파이토치를 활용한 딥러닝 


* 1강 파이토치를 활용한 데이터 로드하기, 기초 모델 만들기
  https://github.com/mgsong83/Deeplearning/blob/main/pytorch/01_Basic.ipynb

  - MNIST 예제로 보는 인공 신경망 쌓기
  - Pytorch Lightning 모듈을 활용한 Train 구현하기
  
* 2강 기초 모델 리뷰 & 개선하기
  https://github.com/mgsong83/Deeplearning/blob/main/pytorch/02_Basic_Continue.ipynb
  - 1강에서 만들었던 모델 리뷰
  - 크로스 엔트로피에서 진행되는 것 (onehot encoding 과 softmax를 자동으로 해준다!)
  - Validation step 추가하기
  - Logger 설정하기
  - Predict 해보고 결과 확인 
  
* 3강 모듈을 만드는 여러가지 방법
  https://github.com/mgsong83/Deeplearning/blob/main/pytorch/03_Build_module.ipynb
  - Pytorch, Pytorch_Lightning을 활용해서 모델을 만드는 방법
  - 리스트, 딕셔너리, for 문을 활용한 모듈 만들기
  - Lightning sequantial 을 사용하는 방법 (Keras처럼)
  - For Loop 을 활용하는 방법

*4강 만든 모듈을 시각화 하는 방법
  https://github.com/mgsong83/Deeplearning/blob/main/pytorch/04_Model_visualization.ipynb
  - 1, 2강에서 만들었던 모듈 시각화
  - ONNX를 활용한 visualization

----

## 텐서플로(케라스)를 활용한 딥러닝

* 1강 케라스를 활용한 회귀 실습

  - Keras 로드하고, 데이터 준비하기
  - Toy MC 데이터에 대해 회귀 분석해보기
  - 선형 -> 비선형 -> 초월함수까지 학습하고 예습하기
  
* 2강 케라스로 전기요금 맞춰보기 (Feature Engeering과 신경망 튜닝)

  - 전기요금 구조 (누진제 + 복잡한 할인제도)
  - Null model 만들어서 비교하기 (선형회귀)
  - 선형회귀보다는 잘 맞추는 모델 만들기


* 3강 케라스로 회귀하듯이 손글씨 분류해보기 ("8", "9" 두 개만 분류해보기)

  - MSE를 활용한 분류 도전
  - 회귀로 예측한 값의 해석
  - 예측결과의 분포와 해석
