# Mediapipe_Jihwa

## 1. 지화란?

농아인을 위해 한글 자음,모음을 손으로 나타내는 것을 의미한다.

![image](https://user-images.githubusercontent.com/83216197/134819066-749d3d6f-23ee-4526-bff2-36e94977470f.png)

출처 : https://blog.naver.com/holyjohn85/150000115485

## 2. 개발 환경

1. 손 마디마디의 좌표값을 얻기 위해 오픈소스인 MediaPipe 사용

![image](https://user-images.githubusercontent.com/83216197/134819170-125fe974-783a-4f4c-9d80-e50e8705407e.png)

출처 : https://google.github.io/mediapipe/solutions/hands.html

2. 좌표값들의 변화에 따른 값을 지정하기 위해 시계열 분석 LSTM을 사용하기 위한 Tensorflow

## 3. Data.py

OpenCv를 통해 카메라에 인식하고자 하는 데이터 설정 후 동작 수행시간, 동작 대기 시간등을 조절하여 Numpy Array로 저장

![image](https://user-images.githubusercontent.com/83216197/134819740-8ccaec42-c36e-4f3d-b859-d4fc382c2d10.png)

![image](https://user-images.githubusercontent.com/83216197/134819826-ec163042-36f6-404f-b9bf-e8444bcd2c64.png)
