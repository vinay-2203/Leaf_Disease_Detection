# 🌿 Leaf Disease Detection using CNN

A deep learning project to automatically detect and classify plant leaf diseases using a Convolutional Neural Network (CNN) trained on the **PlantVillage** dataset.

---

## 📌 Project Overview

This project aims to assist farmers, agricultural researchers, and hobbyists in identifying plant leaf diseases quickly and accurately through image classification.

Using a CNN model, the system learns visual patterns of healthy and diseased leaves and predicts the disease category when a new image is provided.

---

## 🧠 Model Architecture

- Input Image Size: `64x64` (resized and normalized)
- Layers:
  - Multiple `Conv2D` + `ReLU` + `MaxPooling`
  - `Flatten`
  - Dense layers with `Softmax` at the end for multi-class classification
- Loss Function: `categorical_crossentropy`
- Optimizer: `Adam`

---

## 📁 Dataset

- Dataset used: **PlantVillage Dataset**
- Categories: Healthy, Leaf Blight, Leaf Spot, Rust, etc.
- Image Split:
  - Training Set: 80%
  - Validation Set: 20%
- Images were resized and normalized for consistent model input.

---

## 🚀 How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/leaf-disease-detection.git
   cd leaf-disease-detection
