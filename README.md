# Smart Surveillance: Real-Time Face Mask Detection Using MobileNetV2
This project implements a real-time face mask detection system using deep learning and computer vision. Leveraging the MobileNetV2 , the system detects whether a person is wearing a mask or not using live video input from a webcam or video stream.
🚀 Features
Real-time face detection using Haar Cascade classifiers (OpenCV)
Mask classification using fine-tuned MobileNetV2
Accuracy: 98.32%, F1-Score: 0.98 on 1908 test samples
Output rendering with bounding boxes (green = mask, red = no mask)
🤖 Model Overview
Pre-trained MobileNetV2 used as a feature extractor
Custom classification head with dropout and dense layers
Trained on augmented dataset with real-world and synthetic images

Dataset - https://www.kaggle.com/datasets/shiekhburhan/face-mask-dataset?select=FMD_DATASET



