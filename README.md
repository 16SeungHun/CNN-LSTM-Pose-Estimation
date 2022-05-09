# CNN-LSTM-Pose-Estimation
NIA Research project


자신의 Dataset으로 Train 및 Test가 가능합니다.

학습 데이터 셋의 정중앙 RGB값을 추출하는 과정을 거칩니다(데이터가 제대로 들어갔는지 확인)

높이/너비를 64/64로 변환해주고, 자신의 Dataset의 Classes list에 이름을 적어줍니다.

Train/Test는 4:1로 나눴습니다.

처음 학습되는 모델은 CNN 단일 모델이며

두번째로 학습되는 모델은 CNN + LSTM입니다.

TOPROCK TEST 비디오 링크는 다음과 같습니다.

## https://www.youtube.com/watch?v=X1hullry6PU

정답 label : Toprock
