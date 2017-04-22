# TensorFlow CNN-Ensemble Learning with Big-MNIST 

by [Sungchi](http://facebook.com/sungchi)

## 과정 요약

1. infimnist로 mnist training을 변형해 110만 장을 만든다. (메모리 오류 안나는 수준) 
2. tensorflow api로 불러온 데이터 중 training data와 validation data를 합친다.
3. 랜덤으로 training set을 여러벌 만든다. 
4. 앙상블용 신경망을 x개 만들어 신경망당 x번 씩 학습시킨다. 
5. 학습한 신경망 모델마다 test-set으로 예상값을 기록한다. 
6. test-set 결과값을 앙상블해서 최종 정확도를 확인한다.

한 줄 요약: mnist training set을 110만 장 만들고 랜덤 training set으로 신경망 여러개 만들어 결과값을 모아 오차를 줄인다. 
