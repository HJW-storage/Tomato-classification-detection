# 토마토 탐지 및 분류(초록색, 중간, 빨간색)

이미지 크롤링을 통한 데이터셋을 이용해 YOLOv4 model 학습(using google colab)

# 시연영상
![test_img](https://user-images.githubusercontent.com/113449410/231201778-87bd7c35-4032-4ce6-adf7-8ceacf1b61d5.png)
![test_mp4](https://user-images.githubusercontent.com/113449410/231202337-53836d5c-e8be-4ddc-a128-09ce6865d1e7.mp4)

# 간단 사용법
레포지토리 내 **yolov4** 폴더는 4개의 custom file이 들어있습니다.
(i.e. **yolov4-custom.cfg**, **obj.data**, **obj.names** and **process.py**) except **obj.zip**(labeled images). 

**obj.zip** 파일은 yolo format으로 레이블링된 텍스트 파일을 포함합니다. 
 
**<ins>NOTE</ins>**
**yolov4-custom.cfg**, **obj.data**, **obj.names** 3개의 파일을 본인이 찾고자 하는 class에 맞게 수정하여 사용하시면 됩니다.
(본인의 경우는 red, medium, green 3가지 class 사용)



## YOLOv4 model training을 위한 코랩노트북

https://colab.research.google.com/drive/16biTYL3mgmbJghKDcjzKArI81vnGuYZr#scrollTo=Py0DQRy4HHDH

## 사용법 설명 블로그

https://dohyeon.tistory.com/9?category=1006878

## 참조

[AlexeyAB GitHub](https://github.com/AlexeyAB/darknet/)
[TECHZIZOU](https://techzizou.com/train-a-custom-yolov4-detector-using-google-colab-tutorial-for-beginners/)
