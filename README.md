## 🫁 Lung Cancer Detection Using Deep Learning (CNN)

📖 Overview :

 Lung cancer is one of the leading causes of cancer-related deaths worldwide. Detecting the disease at an early stage significantly improves survival rates. Manual examination of CT scan images is time-consuming and depends heavily on the expertise of radiologists.This project presents a Deep Learning-based Lung Cancer Detection System that automatically classifies CT scan images into Cancerous and Normal classes using a Convolutional Neural Network (CNN).To evaluate the effectiveness of Deep Learning, the project also compares the CNN model with several traditional Machine Learning classification algorithms.The final trained model is integrated into a Streamlit web application, allowing users to upload CT scan images and receive instant predictions.

---
## 🎯 Objectives:
- Detect lung cancer at an early stage ,
- Automate CT scan image classification,
- Compare Deep Learning with traditional Machine Learning algorithms,
- Assist healthcare professionals with AI-assisted diagnosis,
- Provide a simple and interactive web interface.
---

## ✨ Features :
- CT Scan Image Upload
- CNN-based Lung Cancer Detection
- Binary Classification
- 🟢 Normal 🔴 Cancerous
- Real-time Prediction
- User-friendly Streamlit Interface
- Image Preprocessing Pipeline
- Confidence Score
- Comparison with Multiple ML Algorithms

---

## 🧠 Machine Learning Algorithms Implemented :
 The project includes implementation and comparison of the following Machine Learning algorithms:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

These algorithms were evaluated to compare their performance with the CNN model.

---

## 🧠 CNN Architecture :
The final Deep Learning model is developed using TensorFlow and Keras.

## Architecture:
- Conv2D (16 Filters)
- MaxPooling2D
- Conv2D (32 Filters)
- MaxPooling2D
- Conv2D (64 Filters)
- MaxPooling2D
- Flatten Layer
- Dense Layer (512 Units)
- Output Layer (Sigmoid Activation)

## 🔄 Project Workflow :


🛠 Technologies Used :
<img width="815" height="428" alt="Screenshot 2026-06-29 202734" src="https://github.com/user-attachments/assets/0577e2e4-ecb3-4718-9074-c4a55d6d3247" />

---

## ⚙ Image Preprocessing :
The CNN model performs the following preprocessing steps:
- Image Resizing
- Pixel Normalization
- Image Rescaling
- Batch Generation
- Binary Label Encoding

ImageDataGenerator is used to prepare the training and testing datasets.

## 📊 Results :
The CNN model successfully classifies Lung CT Scan images into:
- 🟢 Normal
- 🔴 Cancerous
Compared with traditional Machine Learning algorithms, the CNN model demonstrates superior performance in learning complex image features directly from CT scan images.

## 📷 Application Preview
