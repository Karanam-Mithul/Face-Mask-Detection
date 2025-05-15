# Smart Surveillance: Real-Time Face Mask Detection Using MobileNetV2
This project implements a real-time face mask detection system using deep learning and computer vision. Leveraging the MobileNetV2 , the system detects whether a person is wearing a mask or not using live video input from a webcam or video stream.<br>
🚀 Features<br>
- **Real-time face detection using Haar Cascade classifiers (OpenCV)**<br>
- **Mask classification using fine-tuned MobileNetV2**<br>
- **Accuracy: 98.32%, F1-Score: 0.98 on 1908 test samples**<br>
- **Output rendering with bounding boxes (green = mask, red = no mask)**<br>
🤖 Model Overview<br>
- **Pre-trained MobileNetV2 used as a feature extractor**<br>
- **Custom classification head with dropout and dense layers**<br>
- **Trained on augmented dataset with real-world and synthetic images**<br>
<br>
Dataset - https://www.kaggle.com/datasets/shiekhburhan/face-mask-dataset?select=FMD_DATASET



