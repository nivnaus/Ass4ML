# 🌸 Flower Classification using CNN Transfer Learning

---

## 📌 Project Overview

This project focuses on the application of **Convolutional Neural Networks (CNNs)** for image classification.  
We utilize **Transfer Learning** with four pre-trained models — **VGG19**, **ResNet50**, **InceptionResNetV2** and **YOLOv5** — to classify flower images from the **Oxford 102 Flowers Dataset**.

---

## 📊 Dataset

- **Primary Dataset:** Oxford 102 Flowers Dataset  
- **Dataset Link:**  
  https://www.robots.ox.ac.uk/~vgg/data/flowers/102/
- **Additional Datasets:**  
  No additional images or external repositories were used in this project.

---

## ⚙️ Implementation Details

- **Programming Language:** Python
- **Deep Learning Frameworks:**
  - TensorFlow / Keras (VGG19)
  - PyTorch (YOLOv5)

- **Data Splitting:**
  - Training set: **50%**
  - Validation set: **25%**
  - Test set: **25%**
  - The random split procedure was performed **twice** to ensure stability and consistency.

- **Model Output:**
  - Both models are **probabilistic**
  - Each model outputs a probability distribution over **102 flower categories**

## 📈 Minimum Performance Requirement

- **Accuracy Target:**  
  In accordance with the assignment requirements, at least one model achieved **more than 70% accuracy** on the test set.

---

## ✅ Summary

This project demonstrates the effectiveness of CNN-based transfer learning techniques for multi-class image classification using a real-world dataset.

---
