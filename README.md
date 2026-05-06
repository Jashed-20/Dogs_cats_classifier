# 🐶🐱 Dogs vs Cats Classification using Transfer Learning

This project is a deep learning image classification model that distinguishes between dogs and cats using **Transfer Learning (MobileNetV2)**.

---

## 📌 Project Overview
The goal is to build a robust image classifier that can accurately predict whether an input image contains a dog or a cat.  
We use a pre-trained CNN (MobileNetV2) and fine-tune it on the Kaggle Dogs vs Cats dataset.

---

## 📂 Dataset
- Dataset: Kaggle Dogs vs Cats Competition  
- Link: https://www.kaggle.com/c/dogs-vs-cats  
- Images are resized to **224x224** for MobileNet compatibility.

---

## 🧠 Model Architecture
- Base Model: MobileNetV2 (pre-trained on ImageNet)
- Added Layers:
  - Global Average Pooling
  - Dense Layer (ReLU)
  - Dropout Layer
  - Output Layer (Sigmoid for binary classification)

---

## ⚙️ Preprocessing
- Image resizing → 224x224
- Normalization (pixel values / 255)
- Train-test split
- Label encoding (Dog = 1, Cat = 0)

---

## 📊 Results
- Training Accuracy: *XX%*
- Validation Accuracy: *XX%*

*(Replace XX with your actual values)*

---

## 📈 Visualizations
- Training vs Validation Accuracy Plot
- Training vs Validation Loss Plot

---

## 🚀 How to Run

### 1. Clone the repository
```bash
git clone https://github.com/your-username/dogs-vs-cats-transfer-learning.git
cd dogs-vs-cats-transfer-learning
