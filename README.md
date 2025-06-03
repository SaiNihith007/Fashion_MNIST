# 👗 Fashion MNIST Classification

This project explores advanced image classification techniques on the Fashion MNIST dataset using **Convolutional Neural Networks (CNN)** and a **Mini ResNet architecture**, with a strong emphasis on **model interpretability** via Grad-CAM.

---

## 📦 Project Overview

Fashion MNIST contains 70,000 grayscale images of clothing items across 10 categories. The goal of this project was to:

- **Explore and compare deep learning models** to identify the most effective architecture for image classification.
- **Tune and optimize** CNN and Mini ResNet architectures through systematic experimentation.
- **Interpret model decisions** using Grad-CAM visualizations for transparency.

This was treated as an end-to-end deep learning pipeline — from preprocessing and training to evaluation and explainability.

---

## 🧠 Techniques Used

- **Custom CNN** with convolutional and pooling layers
- **Mini ResNet** with residual blocks and skip connections
- **Grad-CAM** to visualize class activation maps
- **PCA & t-SNE** for exploratory data visualization

---

## 📊 Results Summary

After multiple tuning iterations, the **Mini ResNet** architecture achieved the highest performance.

| Metric     | Training | Validation | Test     |
|------------|----------|------------|----------|
| Accuracy   | 94.40%   | 92.28%     | 92.95%   |
| Precision  | 94.83%   | 92.44%     | 93.08%   |
| Recall     | 94.77%   | 92.28%     | 92.95%   |
| F1 Score   | 94.78%   | 92.33%     | 92.98%   |
| Loss       | 0.1541   | 0.2226     | 0.1954   |

---



## ⚙️ Dependencies

Before running the project, ensure that all required dependencies are installed.

### Using `requirements.txt`

1. Open a terminal or command prompt  
2. Navigate to the project directory  
3. Run:

```bash
pip install -r requirements.txt
```

---

## 📂 Data Organization

Before running the code, unzip the `data.zip` file (included in the repo). This will create a folder named `Data/` containing the training, validation, and test image data:

```bash
unzip data.zip
```

## 🚀 Running the Project

To evaluate the project, run the main notebook:

```bash
cd training
jupyter notebook main.ipynb
```