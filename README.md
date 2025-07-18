# 💳 Credit Card Fraud Detection using Machine Learning

This project aims to build a reliable machine learning model to detect fraudulent credit card transactions. Leveraging advanced data preprocessing techniques and supervised learning algorithms, the system identifies suspicious patterns to prevent financial fraud.

## 🚀 Project Overview

Credit card fraud is a growing concern in the financial industry. This project uses a dataset of real transactions labeled as fraudulent or genuine. The main objective is to build a model that can effectively detect fraudulent activity with high accuracy and low false positives.

## 📂 Dataset

- The dataset used is highly imbalanced and contains anonymized features (V1–V28), time, amount, and class (0 = genuine, 1 = fraud).
- Source: [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## 🧠 Techniques Used

- **Data Preprocessing**: Missing value handling, feature scaling, and dealing with class imbalance using SMOTE.
- **Exploratory Data Analysis (EDA)**: Insightful visualizations to understand transaction patterns.
- **Model Training**: Logistic Regression, Random Forest, XGBoost, and other algorithms.
- **Evaluation Metrics**: Precision, Recall, F1-Score, Confusion Matrix, ROC-AUC.

## 🛠 Tools & Libraries

- Python
- scikit-learn
- pandas
- matplotlib / seaborn
- imbalanced-learn (SMOTE)
- XGBoost

## 📈 Results

The best-performing model achieved:
- **Accuracy**: ~99%
- **Precision**: ~92%
- **Recall**: ~87%
- **ROC-AUC**: ~98%

## 📌 Key Features

- End-to-end pipeline from data loading to evaluation
- Handles data imbalance effectively
- Comparative model performance analysis
- Clean and modular code for reproducibility

- 📚 Future Improvements
Integration with real-time data APIs

Deployment as a web service using Flask/Streamlit

Use of deep learning models like AutoEncoders for anomaly detection

📌 Author
Yatharth Kashyap
Connect with me on LinkedIn https://www.linkedin.com/in/yatharth-a36922280/
Feel free to contribute, fork, or give feedback!
