# Real-Time-Face-Mask-Detection

This project provides real-time face mask detection using computer vision and deep learning techniques. The implementation includes scripts for detecting face masks in static images, video files, and real-time webcam streams.

## Introduction

Amidst the COVID-19 pandemic, the World Health Organization (WHO) has mandated the use of masks as a crucial preventive measure against the spread of the deadly virus. In response to this imperative, I have undertaken the development of a machine learning project—Real-time Face Mask Detector with Python

## Dependencies
- Python 3.x
- OpenCV
- TensorFlow
- Keras
- imutils

## Setup
1. Clone the repository:

```bash
git clone https://github.com/your-username/FaceMaskDetection.git
cd FaceMaskDetection
```

## Usage
### 1. Face Mask Detection from Static Images
```bash
python script_static_image.py
```
Provide the path to the input image when prompted.

### 2. Face Mask Detection from Video
```bash
python script_video.py
```
The script will read frames from the specified video file.

### 3. Real-Time Face Mask Detection from Webcam Stream
```bash
python script_realtime_detection.py
```
Uses the webcam to perform real-time face mask detection.


## Training Loss and Accuracy

Include visualizations of the training loss and accuracy over epochs for the mask classification model.

### Loss Plot
![Loss Plot](https://github.com/Rahulshah8383/Real-Time-Face-Mask-Detection/blob/main/Image/loss.png)

### Accuracy Plot
![Accuracy Plot](https://github.com/Rahulshah8383/Real-Time-Face-Mask-Detection/blob/main/Image/accuracy.png)


## Dataset Information

### COVID Face Mask Detection Dataset

The dataset used for training and evaluating the face mask detection model is the "COVID Face Mask Detection Dataset." It consists of approximately 1006 images, equally distributed among two distinct types: images with people wearing face masks and images without face masks.


#### Sample Images

![With Face Mask](https://github.com/Rahulshah8383/Real-Time-Face-Mask-Detection/blob/main/Image/Image_with_mask.png) ![Without Face Mask](https://github.com/Rahulshah8383/Real-Time-Face-Mask-Detection/blob/main/Image/without_mask.png)

### Data Augmentation

To enhance the diversity of the dataset and improve the model's robustness, data augmentation techniques such as rotation, flipping, and zooming were applied during the preprocessing stage.

Download the [dataset](https://www.kaggle.com/datasets/prithwirajmitra/covid-face-mask-detection-dataset/code)


