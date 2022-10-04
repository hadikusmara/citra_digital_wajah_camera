# Belajar-Opencv

## 1. Akses Webcam Laptop dan Crop
### Akses Webcam
- import cv2 
- cam = cv2.VideoCapture(0)
- ret, frame = cam.read()
- cv2.imshow('Video', frame)

### Crop
- hight, width, _ = frame.shape
- frameKiri = frame[0:hight, 0:int(width/4)]
- frameKanan = frame[0:hight, int(width/4):width]

run  pproject
>> python  -u main.py
coba nanti tampil mengunakan webcame

