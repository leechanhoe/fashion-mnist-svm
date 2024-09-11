# fashion-mnist-svm
2023-2학기 머신러닝 fashion-mnist-svm 이미지 분류 팀 프로젝트입니다.

<br>
<br>
<br>

## 정확도를 높이기 위해 사용한 방법

1. 10개를 분류하는 svm 모델로 10개의 이미지 중 확률이 제일 높다고 판단한 2개의 이미지를 선정합니다.
2. 사전에 가능한 조합(10 C 2 = 45개)의 svm 이진 분류기를 학습하여 준비한 후, 45개의 이진 분류기 중 1단계에서 판단한 2개의 해당 이미지를 분류하는 svm 모델을 사용해 정답을 선정합니다.

<br>
<br>
<br>

## 참고

![confusion_matrix](https://github.com/user-attachments/assets/b5f33a31-c7aa-4f65-9ac3-2fa3a5e5481a)
