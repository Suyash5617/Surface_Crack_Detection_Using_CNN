# 🏭 Industrial Surface Crack Detection System using CNN

## 🧠 Project Overview
This project is a Deep Learning-based Industrial Surface Crack Detection System using a Convolutional Neural Network (CNN). It classifies images into two categories: Crack and No Crack. The system includes dataset preprocessing, augmentation, CNN model training, evaluation, and single image prediction.

---

## 🚀 Features
- Automatic dataset splitting (Train / Validation / Test)
- Image preprocessing and augmentation
- Deep CNN model for image classification
- Training & validation accuracy/loss visualization
- Confusion matrix and classification report
- Model saving for reuse
- Single image prediction support
- Industrial-level pipeline implementation

---

## 🏗️ Workflow

Dataset (Crack / NoCrack)
↓
Data Splitting (70/15/15)
↓
Image Augmentation
↓
CNN Model Training
↓
Validation & Evaluation
↓
Confusion Matrix Analysis
↓
Model Saving
↓
Single Image Prediction

---

## 🧠 CNN Architecture
- Conv2D (32) + BatchNorm + MaxPooling  
- Conv2D (64) + BatchNorm + MaxPooling  
- Conv2D (128) + BatchNorm + MaxPooling  
- Conv2D (256) + BatchNorm + MaxPooling  
- Flatten  
- Dense (256) + Dropout  
- Dense (128) + Dropout  
- Output Layer (Sigmoid)

---

## 🛠️ Tech Stack
Python, TensorFlow, Keras, NumPy, Matplotlib, Scikit-learn, OpenCV/PIL

---
