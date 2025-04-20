# 🧠 ImageClassify-CIFAR10

[![GitHub stars](https://img.shields.io/github/stars/Shashwat-19/ImageClassify-CIFAR10?style=social)](https://github.com/Shashwat-19/ImageClassify-CIFAR10/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org)

---

![CIFAR10 Banner](https://github.com/Shashwat-19/ImageClassify-CIFAR10/raw/main/Assets/Image%20banner.jpeg)

## 🧭 Overview
**ImageClassify-CIFAR10** is a deep learning project built using **TensorFlow** and **Keras** that classifies images from the **CIFAR-10** dataset. The project includes a custom CNN model, training visualizations, confusion matrix analysis, and misclassified sample exploration.

---

## 📦 Latest Version: [v1.0](https://github.com/Shashwat-19/ImageClassify-CIFAR10/releases/tag/v1.0)
This version includes the full training workflow, evaluation metrics, and all visual output modules.

---

## ✨ Features

- 🖼️ **CIFAR-10 Dataset** — Contains 60,000 32x32 color images across 10 classes.
- 🧠 **Custom CNN Architecture** — Built and trained from scratch.
- 📈 **Training Visuals** — Loss and accuracy charts for both training and validation.
- 📊 **Confusion Matrix** — Analyze class-wise performance.
- 🧪 **Filter Visualization** — See what early convolutional layers are learning.
- ❌ **Misclassified Samples** — Understand model weaknesses and limitations.

---

## 🏷️ CIFAR-10 Classes
```
airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
```

## 🧠 Model Architecture
```
Input (32x32x3)
↓
Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Conv2D → ReLU → MaxPooling
↓
Flatten → Dense → Dropout → Softmax
```
---
## 📁 Project Structure

```
ImageClassify-CIFAR10/
├── Assets/
│   └── Image banner.jpeg       # Project banner
├── cifar10_classifier.py       # Model training and evaluation script
├── .DS_Store                   # macOS system file (optional to delete)
└── README.md                   # Documentation
```
---

## 🚀 Run Locally

```
# Clone the repository
git clone https://github.com/Shashwat-19/ImageClassify-CIFAR10.git
cd ImageClassify-CIFAR10

# Install dependencies
pip install -r requirements.txt

# Run the model training script
python cifar10_classifier.py
```
---

## 🧰 Tech Stack

**Language:** Python 🐍

**Libraries:** TensorFlow, NumPy, Matplotlib, Seaborn, scikit-learn

**IDE:** Google Collab

---

## 📂 Output Files
```
         File               |             Description
----------------------------|-------------------------------------------
loss_accuracy_plot.png      |  Training/validation loss & accuracy chart
confusion_matrix.png        |  Model performance across 10 classes
filters_visualization.png   |  First-layer filter outputs
misclassified_samples.png   |  Examples where the model failed
```

## 📖 Documentation

All logic is commented and structured inside cifar10_classifier.py.
Further notes and tutorials will be shared soon on my blog.

---

## 🔒 License

This project is licensed under the MIT LICENSE. See the [LICENSE](https://github.com/Shashwat-19/ImageClassify-CIFAR10/blob/main/LICENSE) file for more info.

---

## 📩 Contact  
### Shashwat  
**Software Developer | Cloud & DevOps Enthusiast**

**🔹 Java Backend Development**<br>
**🔹 Cloud Architecture & Containerization**<br>
**🔹 DevOps & Scalable Systems**

### 🚀 Open Source | Tech Innovation  
Passionate about building scalable applications and contributing to transformative tech solutions.

### 📌 Find me here:  
[<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />](https://github.com/Shashwat-19)  [<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />](https://www.linkedin.com/in/shashwatk1956/)  [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:shashwat1956@gmail.com)  [<img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" />](https://hashnode.com/@Shashwat56)
