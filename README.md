# 🔢 MNIST Digit Classification using CNN

A deep learning project to classify **handwritten digits (0–9)** using a **Convolutional Neural Network (CNN)**. The model is trained on the **MNIST dataset**.

---

## 📌 Project Overview

The **MNIST dataset** is a benchmark dataset in machine learning and computer vision. It consists of grayscale images of handwritten digits.

This project builds a **CNN model with TensorFlow/Keras** to classify digits with high accuracy.

---

## 📂 Dataset

* **Source:** [MNIST Dataset](http://yann.lecun.com/exdb/mnist/) (also available via `keras.datasets.mnist`)
* **Training Samples:** 60,000
* **Test Samples:** 10,000
* **Image Size:** 28 × 28 pixels (grayscale)
* **Classes:** 10 (digits 0–9)

---

## ⚙️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge\&logo=plotly\&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge\&logo=tensorflow\&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge\&logo=keras\&logoColor=white)

---

## 🛠️ Project Workflow

### 🔹 Data Preprocessing

* Loaded MNIST dataset from `keras.datasets`
* Normalized pixel values (0–255 → 0–1)
* Reshaped data for CNN input (`28x28x1`)
* One-hot encoded target labels

### 🔹 CNN Architecture

* **Conv2D + ReLU + MaxPooling** layers
* **Flatten** layer
* **Dense (Fully Connected)** layers
* **Output layer** with Softmax activation

### 🔹 Model Training

* **Optimizer:** Adam
* **Loss Function:** Categorical Crossentropy
* **Metrics:** Accuracy
* Trained for multiple epochs with batch size tuning

### 🔹 Evaluation

* Achieved **\~99% training accuracy**
* Achieved **\~98% test accuracy**
* Visualized predictions with sample test images

---

## 📊 Results

✔️ High accuracy (>98%) on test data

✔️ Robust CNN architecture with minimal overfitting

✔️ Correctly classifies handwritten digits
