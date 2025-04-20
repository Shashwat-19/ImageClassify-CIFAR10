# 🧠 ImageClassify-CIFAR10

[![GitHub stars](https://img.shields.io/github/stars/Shashwat-19/ImageClassify-CIFAR10?style=social)](https://github.com/Shashwat-19/ImageClassify-CIFAR10/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org)

---

![CIFAR10 Banner](https://github.com/Shashwat-19/ImageClassify-CIFAR10/raw/main/Assets/Image%20banner.jpeg)


## 🧭 Overview  
**ImageClassify-CIFAR10** is a deep learning project built with TensorFlow and Keras that classifies images from the **CIFAR-10** dataset using a custom Convolutional Neural Network (CNN). It includes training logs, visualizations, filter visual inspection, confusion matrix analysis, and examples of misclassified outputs.

---

## 📦 Latest Version: [v1.0](https://github.com/Shashwat-19/ImageClassify-CIFAR10/releases/tag/v1.0)

This version includes full training workflow, evaluation metrics, and visual outputs.

---

## ✨ Features

- 📦 **CIFAR-10 Dataset** – 10 real-world object classes like cats, trucks, ships, and more.
- 🧠 **Custom CNN Model** – Trained from scratch on CIFAR-10 images.
- 📈 **Loss & Accuracy Graphs** – Training and validation visualizations.
- 📊 **Confusion Matrix** – Identify classification performance across all classes.
- 🔍 **Filter Visualization** – View first-layer convolutional filters.
- ❌ **Misclassified Samples** – Display and analyze where the model fails.

---

## 📁 Dataset Classes

airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

yaml
Copy
Edit

---

## 🧰 Tech Stack

- **Language**: Python  
- **Libraries**: TensorFlow, NumPy, Matplotlib, Seaborn, scikit-learn  

---

## 🧠 Model Architecture

```bash
Input 
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

```bash
ImageClassify-CIFAR10/
├── assets/                         
│   └── banner.jpg                 # Project banner image
├── cifar10_classifier.py          # Main model training script   
├── .DS_Store         
└── README.md                      # Documentation
```

---

## 🧪 Installation

Install required dependencies using:

```bash
pip install -r requirements.txt
```
▶️ Run the Project

# Clone the repository
```
git clone https://github.com/Shashwat-19/ImageClassify-CIFAR10.git
cd ImageClassify-CIFAR10

python cifar10_classifier.py
```

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





