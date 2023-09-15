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

  - 1강에서 만들었던 모델 리뷰
  - 크로스 엔트로피에서 진행되는 것 (onehot encoding 과 softmax를 자동으로 해준다!)
  - Validation step 추가하기
  - Logger 설정하기
  - Predict 해보고 결과 확인 
  
* 3강 모듈을 만드는 여러가지 방법
  
  - Torch 또는 Lightning Moudle 을 상속 받는 컨테이너 (init에서 셋업하고, forward로 직접 연결)
  - Lightning sequantial 을 사용하는 방법 (Keras처럼)
  - For Loop 을 활용하는 방법


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


