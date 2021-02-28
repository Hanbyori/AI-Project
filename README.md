# 육군사령부 인공지능(AI) 공모전
개발 환경 : Python, Pytorch, Tensorboard, Unity

<br/><br/><br/>

## Step1. 목표를 향해 나아가기
Agent가 스스로 판단하여 가장 빠르게 목표에 도달할 수 있게 학습

![Step1](https://user-images.githubusercontent.com/20338405/109161075-fc457e80-77b9-11eb-9cfd-2790b941df90.gif)

<br/>

80만번의 학습 결과
Step: 800000. Time Elapsed: 626.651 s. Mean Reward: 25.462. Std of Reward: 10.457. Training.

![Step1-result](https://user-images.githubusercontent.com/20338405/109161871-e71d1f80-77ba-11eb-92be-8b29ca0336ea.PNG)

<br/><br/><br/>

## Step.2 Target 배치하기
1번 스텝에서 학습한 모델을 토대로 Target 정보를 입력하여 다시 학습
![Step2](https://user-images.githubusercontent.com/20338405/109424051-6e6dcb80-7a25-11eb-917e-35aa8dce0983.gif)
