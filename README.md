# Indian Sign Language Gesture Recognition using YOLOv8

This project focuses on recognizing *20 static Indian Sign Language (ISL) gestures* using the *YOLOv8 object detection model*. It uses a custom-built dataset and is trained and evaluated entirely on Google Colab using the Ultralytics YOLOv8 library.

---

## 🧠 Project Overview

The goal is to develop a deep learning model that can identify common ISL hand gestures from images. This can help improve gesture-based communication systems, especially for the hearing- and speech-impaired communities.

The YOLOv8s (small) model was chosen for its balance between *speed and accuracy*, making it suitable for real-time gesture detection even on limited hardware.

---

## 📁 Dataset Details

> ⚠️ *The dataset is private and not included in this repository.*

- 20 gesture classes (both one-hand and two-hand)
- ~1200 training images, ~600 test images
- Labeled in YOLO format (.txt files)
- Dataset structured into:
