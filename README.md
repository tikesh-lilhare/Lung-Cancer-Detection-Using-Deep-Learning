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

---
## Working Pipeline
<img width="1024" height="1536" alt="ChatGPT Image Jun 30, 2026, 07_05_28 PM" src="https://github.com/user-attachments/assets/cf7a5b77-2229-46a1-8a82-41d5a80d4a96" />

---
## 📷 Application Preview
## Detection Using Machine Learning
  <img width="1217" height="772" alt="Screenshot 2026-06-30 185242" src="https://github.com/user-attachments/assets/dd9be456-36c8-4e23-970c-0e2d322a3179" />

---

<img width="1346" height="763" alt="Screenshot 2026-06-30 185259" src="https://github.com/user-attachments/assets/7efb00e6-c401-4666-aa98-bd7f503becae" />
<img width="1403" height="827" alt="Screenshot 2026-06-30 185509" src="https://github.com/user-attachments/assets/acd8a709-5ecc-475d-a8be-dd43e30003fd" />

---
## Detection Using CNN
<img width="1245" height="520" alt="Screenshot 2026-06-30 185322" src="https://github.com/user-attachments/assets/4f9eec0d-60c6-4b99-b39f-067b22fbf44a" />
<img width="1392" height="853" alt="Screenshot 2026-06-30 185353" src="https://github.com/user-attachments/assets/6d6b82fc-3eec-41c6-866d-50e02105ad31" />
<img width="1121" height="537" alt="Screenshot 2026-06-30 185410" src="https://github.com/user-attachments/assets/29397f88-a6f6-4f69-8f06-b3e8ba7824ef" />
<img width="1338" height="830" alt="Screenshot 2026-06-30 185615" src="https://github.com/user-attachments/assets/ae4ba06f-8865-40dc-9248-f357125ab807" />

---

## 🚀 Installation

## Clone the repository

- git clone https://github.com/tikesh-lilhare/Lung-Cancer-Detection-Using-Deep-Learning.git

## Move to project directory

- cd Lung-Cancer-Detection-Using-Deep-Learning

## Install dependencies

- pip install -r requirements.txt

## Run Streamlit Application

- streamlit run app.py

## Open Browser

- http://localhost:8501



