# 🌿 Leaf Disease Detection using Deep Learning (CNN)

Accurate identification of plant leaf diseases using a custom-trained Convolutional Neural Network (CNN). This project leverages the **PlantVillage dataset** to classify various types of leaf diseases and assist in early detection and treatment.

---

## 🔍 Project Objective

To develop a deep learning model that can:

- Detect diseases in plant leaf images
- Classify the disease into predefined categories
- Assist farmers and agriculturists with timely diagnosis

---

## 🧠 Model Summary

- **Model Type:** Convolutional Neural Network (CNN)
- **Input Size:** 64×64 RGB images
- **Core Layers:**
  - Multiple `Conv2D + ReLU + MaxPooling`
  - `Flatten → Dense Layers → Softmax`
- **Loss Function:** `Categorical Crossentropy`
- **Optimizer:** `Adam`

- **Accuracy Achieved:** **94.57%**
- **Metrics:** `Accuracy`

---

## 🗃️ Dataset Details

- **Source:** [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Classes:** Healthy, Leaf Spot, Leaf Blight, Rust, and more
- **Total Images:** ~50,000
- **Split:**
  - **80% Training**
  - **20% Validation**

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/leaf-disease-detection.git
cd leaf-disease-detection
