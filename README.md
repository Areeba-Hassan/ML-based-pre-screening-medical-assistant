# Overview:
This project provides an easy to use ML based heart disease pre-screening assistant app for medical workers with minimal to no technical/computational expertise. The app offers dynamic training options to train multiple ML models based on the medical institutions requirements with options for exploratory analysis, feature selection, hyperparameter tuning, re-training and evaluation metrics. By default, the models are trained on the UCI heart disease dataset (kaggle) but every medical institution can use their own patient data to avoid biases or model drift caused due to the particular demographics of the UCI dataset.

# Scope: 
This system focuses on a binary classification problem that predicts if a patient has heart disease or not based on 13 clinical features including age, sex, chest pain type, blood pressure, cholesterol levels, and various cardiac test results. The system is not absolute and can make mistakes. It is essentially designed for use in clinical settings as a decision support tool, not as a replacement for professional medical diagnosis.

# Libraries used: 
Pandas, NumPy, Scikit-learn, Matplotlib/Seaborn, Ngrok, Streamlit
