# FaceMask-Detection

## :hourglass: DESCRIPTION
In the current situation due to Covid-19, there is no proficient face mask detection applications which are presently sought after for transportation implies, thickly populated zones, private regions, enormous scope producers and different endeavors to guarantee security. Additionally, the nonappearance of enormous datasets of 'with_mask' pictures has made this assignment progressively bulky and testing.


## :warning: TECHNOLOGY USED:
1. OpenCV
2. Caffe-based face detector
3. Keras
4. TensorFlow
5. MobileNetV2


## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://drive.google.com/drive/folders/1XDte2DL2Mf_hw4NsmGst7QtYoU7sMBVG?usp=sharing)

This dataset consists of __3835 images__ belonging to two classes:
*	__with_mask: 1916 images__
*	__without_mask: 1919 images__


## :bulb: Working

1. Open terminal. Go into the cloned project directory folder and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. Now detect the face masks in images 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. Detection in real-time video streams
```
$ python3 detect_mask_video.py 
