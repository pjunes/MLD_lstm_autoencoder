# MLD_lstm_autoencoder
기계학습종합설계 프로젝트

DB는 용량이 큰 관계로 포함되어있지 않습니다.
사용한 DB : AI HUB, 기계시설물 고장 예지 센서

Training.ipynb
모델을 학습시키는 파일.

Prediction.ipynb
학습된 모델로 Prediction을 진행하여 결과를 확인하는 파일.

lstm_autoencoder.h5
학습된 모델

mse_1129_1000.pickle
1000개의 파일을 대상으로 진행한 mean square error 값 저장

pred_1129_1000.pickle
1000개의 파일을 대상으로 진행한 prediction의 결과
