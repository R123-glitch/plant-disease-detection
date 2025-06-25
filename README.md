# 🌿 Plant Disease Detection using CNN & Transfer Learning

This project detects **plant leaf diseases** using a **Convolutional Neural Network (CNN)** and **ResNet18 transfer learning**, trained on a large image dataset of diseased and healthy plant leaves.

---

## 🚀 Project Features

- 🔍 Classifies multiple plant diseases with labeled images
- ⚡ Turbo mode: trains under 10s for testing/debugging
- 🧠 Deep Learning with PyTorch (CNN / ResNet18)
- 📈 Live training loss visualization
- 📊 Train & validation accuracy calculation
- 🖼️ Dataset augmentation & preprocessing

---

## 📁 Dataset Used

**Source:** [Kaggle - New Plant Diseases Dataset (Augmented)](https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset)


---

## 🧠 Model Architectures

### 🔸 Option 1: TinyCNN (for fast testing)
- 2 convolutional layers
- 2 max pooling layers
- 2 fully connected layers

### 🔸 Option 2: ResNet18 (for high accuracy)
- Pretrained on ImageNet
- Only final layer is retrained (transfer learning)

---

## ⚙️ How to Run

> Recommended: Run on **Kaggle GPU Notebook** or **Google Colab**

### ✅ Setup

```bash
pip install torch torchvision matplotlib
###Sample Output
Train Accuracy: 85–95% (ResNet, 3–5 epochs)

Validation Accuracy: 75–90%

Loss Graph: 📉 clean convergence

Turbo mode: just checks your pipeline
