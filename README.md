# ANN Customer Churn Prediction

A machine learning web application that predicts whether a customer is likely to churn using an Artificial Neural Network (ANN).

The trained ANN model is integrated with a Streamlit web application where users can enter customer details and receive a churn prediction.

## 🚀 Project Overview

Customer churn prediction helps businesses identify customers who may leave their services.

This project uses an Artificial Neural Network trained on customer data to predict customer churn based on factors such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Credit Card status
- Active Membership status
- Estimated Salary

## 🧠 Machine Learning Model

The project uses an Artificial Neural Network (ANN) built using TensorFlow/Keras.

The machine learning pipeline includes:

1. Data preprocessing
2. Encoding categorical features
3. Feature scaling
4. ANN model training
5. Model evaluation
6. Saving the trained model
7. Integrating the model with Streamlit

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Joblib
- Streamlit
- Git & GitHub

## 📁 Project Structure

```text
ANN-Churn-Prediction/
│
├── app.py
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
├── .gitignore
└── README.md