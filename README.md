# YOLO-Summary
## YOLO源码：
+ https://github.com/pjreddie/darknet
+ https://github.com/AlexeyAB/darknet
非常推荐AlexeyAB的darknet改进版
论文：
+ https://pjreddie.com/media/files/papers/YOLOv3.pdf

YOLOv3复现代码合集涵盖 5 种常用深度学习框架：
- [TensorFlow](#TensorFlow)
- [PyTorch](#PyTorch)
- [Keras](#Keras)
- [Caffe](#Caffe)
- [MXNet](#MXNet)

<a name="TensorFlow"></a>

# TensorFlow

| Project                                                      | Infernece | Train | star |
| ------------------------------------------------------------ | --------- | ----- | ---- |
| [tensorflow-yolov3](https://github.com/YunYang1994/tensorflow-yolov3) | √         | √     | 1837 |
| [yolov3-tf2](https://github.com/zzh8829/yolov3-tf2)          | √         | √     | 795  |
| [tensorflow-yolo-v3](https://github.com/mystic123/tensorflow-yolo-v3) | √         | x     | 666  |
| [YOLOv3-tensorflow](https://github.com/maiminh1996/YOLOv3-tensorflow) | √         | √     | 272  |

<a name="PyTorch"></a>

# PyTorch

| Project                                                      | Infernece | Train | star |
| ------------------------------------------------------------ | --------- | ----- | ---- |
| [PyTorch-YOLOv3](https://github.com/eriklindernoren/PyTorch-YOLOv3) | √         | √     | 2955 |
| [yolov3](https://github.com/ultralytics/yolov3)              | √         | √     | 2686 |
| [pytorch-yolo-v3](https://github.com/ayooshkathuria/pytorch-yolo-v3) | √         | x     | 2291 |
| [YOLO_v3_tutorial_from_scratch](https://github.com/ayooshkathuria/YOLO_v3_tutorial_from_scratch) | √         | x     | 1489 |
| [ObjectDetection-OneStageDet](https://github.com/TencentYoutuResearch/ObjectDetection-OneStageDet/tree/master/yolo) | √         | √     | 1471 |
| [YOLOv3_PyTorch](https://github.com/BobLiu20/YOLOv3_PyTorch) | √         | √     | 442  |
| [PyTorch_YOLOv3](https://github.com/DeNA/PyTorch_YOLOv3)     | √         | √     | 258  |

<a name="Keras"></a>

# Keras

| Project                                                      | Infernece | Train | Star |
| ------------------------------------------------------------ | --------- | ----- | ---- |
| [keras-yolo3](https://github.com/qqwweee/keras-yolo3)        | √         | √     | 4680 |
| [YOLOv3](https://github.com/xiaochus/YOLOv3)                 | √         | x     | 505  |
| [keras-YOLOv3-mobilenet](https://github.com/Adamdad/keras-YOLOv3-mobilenet) | √         | √     | 410  |

<a name="Caffe"></a>

# Caffe

| Project                                                      | Infernece | Train | Star |
| ------------------------------------------------------------ | --------- | ----- | ---- |
| [MobileNet-YOLO](https://github.com/eric612/MobileNet-YOLO)  | √         | √     | 569  |
| [caffe-yolov3](https://github.com/ChenYingpeng/caffe-yolov3) | √         | x     | 273  |
| [Caffe-YOLOv3-Windows](https://github.com/eric612/Caffe-YOLOv3-Windows) | √         | √     | 163  |

<a name="MXNet"></a>

# MXNet

| Project                                                      | Infernece | Train | Star |
| ------------------------------------------------------------ | --------- | ----- | ---- |
| [gluoncv](https://github.com/dmlc/gluon-cv/tree/master/gluoncv/model_zoo/yolo) | √         | √     | 3187 |

### 参考：
+ https://zhuanlan.zhihu.com/p/50170492
+ https://github.com/amusi/YOLO-Reproduce-Summary/blob/master/README.md


## 一、yolo框架的解读：
+ https://zhuanlan.zhihu.com/p/32525231


## 二、500问里目标检测解决的问题和yolo解读
+ [第八章 目标检测]()
+ https://github.com/scutan90/DeepLearning-500-questions

## 三、基于YOLO的项目
### 3.1使用YOLOv3训练、使用Mask-RCNN训练、理解ResNet、模型部署、人脸识别、文本分类等：
+https://github.com/StevenLei2017/AI_projects
### 3.2基于yolo3 与crnn 实现中文自然场景文字检测及识别
![0.png](image/0.png)
+ https://github.com/chineseocr/chineseocr
### 3.3 YOLOv3 in PyTorch > ONNX > CoreML > iOS
![1.png](image/1.png)
+ https://github.com/ultralytics/yolov3
### 3.4YoloV3/tiny-YoloV3+RaspberryPi3/Ubuntu LaptopPC+NCS/NCS2+USB Camera+Python+OpenVINO 
![2.png](image/2.png)
+ https://github.com/PINTO0309/OpenVINO-YoloV3
## 四、YOLO模型压缩：
### 4.1、剪枝：
+ https://github.com/zbyuan/pruning_yolov3
+ https://github.com/coldlarry/YOLOv3-complete-pruning
+ https://github.com/Lam1360/YOLOv3-model-pruning

## 五、YOLO系列
### 5.1 Enriching Variety of Layer-wise Learning Information by Gradient Combination
| Model | Size | mAP@0.5 | BFLOPs |
| :-- | :-: | :-: | :-- |
| EfficientNet_b0-PRN | 416x416 | 45.5 | 3.730 |
| EfficientNet_b0-PRN | 320x320 | 41.0 | 2.208 |
+ https://github.com/WongKinYiu/PartialResidualNetworks
### 5.2 Gaussian YOLOv3: An Accurate and Fast Object Detector Using Localization Uncertainty for Autonomous Driving
![4.png](image/4.png)
+ https://github.com/jwchoi384/Gaussian_YOLOv3
### 5.3 YOLO Nano: a Highly Compact You Only Look Once Convolutional Neural Network for Object Detection
| Model | model Size | mAP(voc 2007) | computational cost(ops) |
| :-- | :-: | :-: | :-- |
| Tiny YOLOv2[13] | 60.5MB | 57.1% | 6.97B |
| Tiny YOLOv3[14] | 33.4MB | 58.4% | 5.52B |
| YOLO Nano | 4.0MB | 69.1% | 4.57B |
+ https://arxiv.org/pdf/1910.01271.pdf
+ https://github.com/liux0614/yolo_nano
### 5.4