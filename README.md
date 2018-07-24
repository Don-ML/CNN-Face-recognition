# CNN-faceid
CNN+tensorflow+python

本项目 有3个Python文件 tensorflow-face-conv.py是CNN网络架构  基于Google的tensorflow框架
tensorflow-face-camera.py是人脸录入 一共录入200张人脸存到image/trainfaces文件夹下，如果没有trainfaces文件下，请自行建一个空的trainfaces文件夹
tensorflow-face.py第一次运行时会检测checkpoint文件夹下是否存在face.ckpt.data-00000-of-00001等文件，若没有则进行train ，如已存在则进行人脸识别，

先执行tensorflow-face-camera.py录入人脸，然后进行tensorflow-face.py进行train 再一次执行tensorflow-face.py进行人脸识别
