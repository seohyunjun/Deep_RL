# Reinforcement Learning

### paper
Deep Q-Network - [Playing Atari with Deep Reinforcement Learning(2013.12)](https://arxiv.org/abs/1312.5602)


<br>

### Code Environment
[OpenAI-gym](https://www.gymlibrary.dev/)

### Code
[CarPole-V1](https://pytorch.org/tutorials/intermediate/reinforcement_q_learning.html)


### Mac setting 
```shell
brew install cmake zlib
pip install 'gym[all]'
```

<br>
[pip install 'gym[all]' error](https://www.pygame.org/wiki/MacCompile)
[딥러닝 분산 학습 관련 연구 - Deep learning travels - 류성원](https://lyusungwon.github.io/assets/publications/DistributedDeepLearningTrainingOverview.pdf)

<br>

## DQN(Deep Q-Network) 

<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B31.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B32.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B33.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B34.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B35.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B36.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B36.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B37.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B38.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B39.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B310.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B311.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B312.jpeg" height=80% width=80% >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/data/CartPole_21.gif" width="75%" height="75%" >
<img src="https://github.com/seohyunjun/Deep_RL/blob/main/1_DQN/%E1%84%89%E1%85%B3%E1%86%AF%E1%84%85%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%83%E1%85%B313.jpg" height=80% width=80% >
