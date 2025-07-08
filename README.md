# 🌿 Plant Disease Detection using CNN

<p align="center">
  <img src="https://img.shields.io/badge/Built%20With-TensorFlow%20%7C%20Keras-orange?style=flat-square"/>

</p>

---

## 📌 Overview

This project aims to detect **plant leaf diseases** using **deep learning (CNN)** with the help of the (https://www.kaggle.com/datasets/emmarex/plantdisease). The model classifies leaves into different categories such as **Tomato_Bacterial_spot**, **Potato_Early_blight**, and **Healthy** based on image input.

---

## 🧠 Model Highlights

- ✅ Built using a **Convolutional Neural Network (CNN)** from scratch
- ✅ Trained on 15+ disease categories from PlantVillage
- ✅ Achieved high accuracy with real-time predictions
- ✅ Supports prediction using custom images

---

## 📂 Dataset

- **Source**: https://www.kaggle.com/datasets/emmarex/plantdisease
- **Format**: Images organized into folders by class (disease name)
- **Total Classes**: 15+
- **Total Images**: 40,000+

---

## 🚀 How It Works

1. Load and preprocess the dataset using `ImageDataGenerator`
2. Build and compile a CNN model using Keras
3. Train the model with 80% of the dataset
4. Validate the model with the remaining 20%
5. Save the model for later use
6. Predict diseases from new images

---

## 📷 Example Prediction

![Sample Prediction](""C:\Users\USER\Desktop\PlantDieasedetection\Screenshot 2025-07-08 235536.png"")

> Input: Leaf image  
> Output: `Tomato___Bacterial_spot`

---

## 🔧 Tech Stack

- Python 3
- TensorFlow / Keras
- NumPy
- Matplotlib
- Google Colab

---


