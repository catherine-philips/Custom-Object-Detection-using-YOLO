# 🏏 Custom Object Detection Using YOLO

## 📄 Overview

This project focuses on leveraging **YOLO (You Only Look Once)**, a real-time object detection algorithm, to detect specific objects using custom datasets. The project is centered around detecting cricket balls and aims to achieve high accuracy in identifying objects in images.

YOLO's architecture allows it to simultaneously predict multiple bounding boxes and class probabilities for objects within an image, making it a popular choice for real-time applications. By training it on a custom dataset, YOLO can be adapted to detect any specific objects, providing robust solutions for various detection tasks.

---

## ✨ Key Features

- **Custom Object Detection**: The project is designed to detect specific objects (like cricket balls)
- **Real-Time Performance**: YOLO's unique architecture ensures fast and efficient object detection, which is crucial for real-time applications such as video analysis.
- **Robust Detection Capabilities**: YOLO can handle multiple object detection in a single image, ensuring accurate and scalable results.
- **Transfer Learning**: Pre-trained YOLO models have been fine-tuned with the custom dataset, improving detection performance for the targeted objects.

---
## 📦 Dataset Source

The dataset used in this project was sourced from **[Roboflow](https://roboflow.com/)**, which provides a streamlined environment for dataset creation, annotation, and augmentation. Roboflow was instrumental in ensuring high-quality data for training the YOLO model.

---
## 📊 Results

After training the YOLO model on the custom dataset, the model demonstrated effective object detection in both images and videos. The trained model is capable of detecting cricket balls in real-time with a high degree of accuracy. Results show the successful identification of objects across various scenarios, including different angles, lighting conditions, and backgrounds.
Below are two sample results from the object detection model on tested images:

<p align="center">
  <img src="https://github.com/catherine-philips/Custom-Object-Detection-using-YOLO/blob/main/YOLO%20Ball%20Detection(1).png" alt="Test Image 1" width="45%" />
  <img src="[path_to_image2](https://github.com/catherine-philips/Custom-Object-Detection-using-YOLO/blob/main/YOLO%20Ball%20Detection.png)" alt="Test Image 2" width="45%" />
</p>
Some key results:
- **Accuracy**: High detection accuracy with minimal false positives.
- **Real-Time Performance**: Capable of processing video streams without significant delay.
- **Generalization**: Robust detection across diverse testing environments.

---

## 🚀 Future Work

There are several potential improvements and future directions for this project:
- **Using camera stream**: Expanding the functionality to include identifying objects over a real-time camera stream.
- **Multi-object detection**: Expand the model to detect multiple objects or classes within the same frame.
- **Improved Model Accuracy**: Further fine-tuning of the model with additional training data.
- **Integration with Object Tracking**: Combine object detection with tracking algorithms to analyze object motion over time in videos.
