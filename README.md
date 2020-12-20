# G20_face_detector

# ★ 프로젝트 결과 ★

## 1. 데이터셋 전처리 과정 완료

- tfrecord 생성, augmentation, prior box 생성 등

- 원본 이미지

![image](https://user-images.githubusercontent.com/39249809/102706043-bd82dc00-42d1-11eb-9389-a0c3ba50a86c.png)


## 2. SSD 모델의 안정적 학습

- multiface detection 결과 이미지

![SSD_Detector1](https://user-images.githubusercontent.com/39249809/102706045-bf4c9f80-42d1-11eb-9d2d-593864e2ee8c.png)
![SSD_Detector2](https://user-images.githubusercontent.com/39249809/102706046-bfe53600-42d1-11eb-8dbc-bcad3842ebf2.png)
![SSD_Detector3](https://user-images.githubusercontent.com/39249809/102706048-c07dcc80-42d1-11eb-9ee8-76c7de79c65c.png)

## 3. 이미지 속 다수의 얼굴에 스티커 적용

- multiface detection 및 스티커 적용 결과 이미지

![SSD_Detector4](https://user-images.githubusercontent.com/39249809/102706049-c1166300-42d1-11eb-9bad-4b8c6a38609e.png)
![SSD_Detector5](https://user-images.githubusercontent.com/39249809/102706050-c1aef980-42d1-11eb-888f-86339c0a60f8.png)

## 4. dlib을 활용해 hog detector로 동일하게 실행해 보기

- SSD 모델보다는 dlib에서 제공되는 hog detector 결과가 더 좋은 것 같다. 

![Hog_Detector1](https://user-images.githubusercontent.com/39249809/102706037-b9ef5500-42d1-11eb-90f2-faa6c80042d1.png)
![Hog_Detector2](https://user-images.githubusercontent.com/39249809/102706039-bbb91880-42d1-11eb-8cc0-1e3797a8a2a0.png)
![Hog_Detector3](https://user-images.githubusercontent.com/39249809/102706041-bc51af00-42d1-11eb-97eb-8685bcf9bc3e.png)
![Hog_Detector4](https://user-images.githubusercontent.com/39249809/102706042-bcea4580-42d1-11eb-9ad1-3d324b7ee595.png)
