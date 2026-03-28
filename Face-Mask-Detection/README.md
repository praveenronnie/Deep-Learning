# Face Mask Detection System

## Overview

This project is a deep learning-based system that detects whether a person is wearing a face mask or not. It uses computer vision and a trained model to perform real-time detection through a webcam.

## Objective

* Detect human faces from video stream
* Classify each face as Mask or No Mask
* Perform real-time detection
* Improve performance under different lighting conditions

## Tech stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* MobileNetV2 (pre-trained model)

## Workflow

Data Collection  
↓  
Data Preprocessing  
↓  
Train/Test Split  
↓  
Model Building  
↓  
Model Training  
↓  
Model Evaluation  
↓  
Real-time Video Capture  
↓  
Face Detection  
↓  
Mask Classification  
↓  
Display Output 


## Data Preprocessing

* Resized images to a fixed size
* Normalized pixel values
* Applied data augmentation (brightness, contrast, flipping)
* Improved model performance for different lighting conditions


## Model Details

* Used MobileNetV2 with transfer learning
* Added custom layers for classification
* Two output classes: Mask and No Mask


## Real-Time Detection

* Captures video using webcam
* Detects faces using OpenCV (Haar cascade)
* Classifies each detected face
* Displays output with bounding box and label
* Press 'esc' key for closing webcam


## Improvements

* Adjusted brightness and contrast to handle low-light conditions
* Used augmentation to make the model more robust