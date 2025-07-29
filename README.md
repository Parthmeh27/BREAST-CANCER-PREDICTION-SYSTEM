# 🧠 Breast Cancer Prediction - End-to-End ML Deployment with Flask & AWS

This project is an end-to-end machine learning pipeline built to predict breast cancer diagnosis (Benign or Malignant) using key medical parameters. The model is deployed using Flask as a web application and hosted on AWS EC2.

## 🚀 Project Highlights

- Trained a **Random Forest Classifier** achieving **95.61% accuracy**
- Built a **Flask web application** to collect user inputs and display predictions
- Designed a simple **HTML front-end** to capture input features
- Deployed the application to **AWS EC2**
- Implemented **predict_proba** to show model confidence level
- Used real-world breast cancer dataset with multiple features

## 📊 Dataset

The dataset used is based on the [UCI Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)), containing medical data such as:
- Radius Mean
- Texture Mean
- Perimeter Mean
- Smoothness Mean
- Compactness Mean  
Target variable: `Diagnosis` (M = Malignant, B = Benign)

## 🛠️ Tech Stack

- **Python 3.9+**
- **Flask**
- **Scikit-learn**
- **Pandas / NumPy**
- **HTML/CSS (Basic)**
- **AWS EC2 (Amazon Linux AMI)**

## 🌐 Flask Application Routes

- `/` - Home page (input form)
- `/predict` - POST endpoint for prediction and rendering output
