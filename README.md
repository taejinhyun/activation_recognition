# activation_recognition

* 자이로스코프, 가속도 센서의 x,y,z 값을 통해 걷기, 서기, 눕기, 앉기, 식사, 5가지 1차 행동을 분류합니다. 
* 1차 행동의 지속시간과 직전 행동을 토대로 낙상, 수면을 추가로 분류합니다.
* 신경망과 머신러닝의 정확도 비교를 위해 두 가지 모두 진행하였고 신경망의 정확도가 압도적으로 높아 이 후 작업은 신경망으로 진행하였습니다.
* lstm(tf)를 사용하였습니다.
