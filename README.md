# 🌸 Flower Classification using Transfer Learning (CNN)

**Assignment No. 4**  
**Submission Date:** 02/02/2026  

---

## 📌 Project Description

This project implements an image classification system for identifying flower types from images using **Convolutional Neural Networks (CNNs)**.  
In accordance with the assignment requirements, we apply **Transfer Learning** using two pre-trained models:

- **VGG19**
- **YOLOv5**

Both models were adapted for multi-class flower classification and evaluated on a standardized dataset.

---

## 📊 Dataset

- **Name:** Oxford 102 Flowers Dataset  
- **Source:**  
  https://www.robots.ox.ac.uk/~vgg/data/flowers/102/
- **Description:**  
  The dataset contains images from **102 different flower categories**.
- **Additional Data:**  
  No external datasets or repositories were used for this assignment.

---

## ⚙️ Implementation Requirements

- **Frameworks & Libraries:**
  - Python
  - TensorFlow / Keras (for VGG19)
  - PyTorch (for YOLOv5)

- **Data Splitting:**
  - Training set: **50%**
  - Validation set: **25%**
  - Test set: **25%**
  - The dataset was split **randomly**.

- **Repetition:**
  - The random split procedure was performed **twice**, using different random seeds, to ensure result consistency.

- **Model Output:**
  - Both models produce **probabilistic outputs**.
  - A **Softmax** layer is used to return the probability distribution over all 102 flower classes.

---

## 📁 Repository Content

- **Source Code:**  
  GitHub repository links are provided as required by the assignment.

- **Models Used:**
  - **VGG19**  
    - Pre-trained on ImageNet  
    - Extended with a custom classification head for 102 classes
  - **YOLOv5**  
    - Adapted from object detection to image classification

---

## 📈 Performance Results

- **Minimum Requirement:**  
  At least one model must achieve **>70% accuracy** on the test set.

- **Results Achieved:**
  - **YOLOv5** achieved approximately **97.7% test accuracy**, significantly exceeding the requirement.
  - VGG19 also demonstrated strong performance, though YOLOv5 achieved the highest accuracy.

---

## ✅ Summary

This project successfully demonstrates the effectiveness of **Transfer Learning** for image classification tasks.  
By leveraging powerful pre-trained CNN architectures, especially YOLOv5, we achieved high classification accuracy while meeting all assignment constraints.

---
