# ML_Crossroad
Machine Learning with DQN in CS496 - Week5 / Python

source code: https://github.com/golbin/TensorFlow-Tutorials/tree/master/12%20-%20DQN


### 파일 설명

- agent.py
  - 게임을 진행하거나 학습시키는 에이전트입니다.
- game.py
  - 게임을 구현해 놓은 파일입니다. 게임의 상태를 화면의 픽셀로 가져오지 않고, 좌표값을 이용하여 계산량을 줄이도록 하였습니다.
- model.py
  - DQN을 구현해 놓은 파일입니다.
  - 논문에서는 CNN 모델을 사용하였지만, 구현을 간단히 하고 성능을 빠르게 하기 위해 기본적인 신경망 모델을 사용합니다.

### 사용법

자가 학습시키기

```
python agent.py --train
```

얼마나 잘 하는지 확인해보기

```
python agent.py
```

텐서보드로 평균 보상값 확인해보기

```
tensorboard --logdir=./logs
```

