# 😷Mask Detection

> vgg-16 모델을 이용한 마스크 착용 여부 구분 프로젝트 <br>
>[최종보고서](https://drive.google.com/file/d/19z7eVsWjs251cFUKMKs7wZXYoL9ellaC/view?usp=sharing)

## 1. 제작기간 & 참여인원

- 2022년 5월 1일 ~ 5월 30일
- 4명

## 2. 데이터

데이터셋 출처 [https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset)

|  | withmask | without mask | total |
| --- | --- | --- | --- |
| test | 483 | 509 | 990 |
| train | 5000 | 5000 | 10000 |
| validation | 400 | 400 | 800 |

train data와 test data가 10:1의 적절한 비율로 이루어져 있고,

총 11790개, 약 12000개의 충분한 양의 데이터로 구성되어 있기 때문에 해당 데이터셋을 선정했다.

### 2.1. 데이터 특징

- 마스크 착용 / 미착용의 사람 이미지
- 데이터의 크기가 각각 다름, 따라서 데이터 크기를 일정하게 맞추는 전처리 작업 필요

### 2.2. 데이터 visualize

## 3. 사용 기술

- Keras
- Tensorflow

## 4. 개발 환경

- Google Colaboratory(python 3.7.13)

## 5. 머신러닝 아키텍처 / 모델

## 6. 학습결과

## 7. 트러블슈팅 경험

## 회고/느낀점
