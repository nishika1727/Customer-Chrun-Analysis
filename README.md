# 🔍 Customer Churn Prediction

This project predicts whether a customer is likely to churn based on their service details using machine learning. It includes data analysis, model building, handling data imbalance with SMOTE, and deploying the model through a Flask web application.

---

## 📌 Overview

Customer churn refers to the loss of clients or customers. Predicting churn helps businesses retain valuable users and reduce revenue loss. This project involves:

- Cleaning and exploring the customer dataset
- Building classification models (Decision Tree and Random Forest)
- Addressing class imbalance using SMOTE
- Deploying a user-friendly web app to predict churn based on input features

---

## 🧰 Technologies Used

- **Language**: Python  
- **Libraries**: pandas, seaborn, matplotlib, scikit-learn, imbalanced-learn  
- **Modeling**: Decision Tree, Random Forest (with and without SMOTE)  
- **Web Framework**: Flask  
- **Frontend**: HTML, CSS (optional)

---

## 🚀 How It Works

1. The user enters customer details through a web form.
2. The app processes these inputs and uses a trained model to predict if the customer will churn.
3. The prediction (Yes/No) is displayed instantly.

---

## 🧪 Model Performance

| Model                   | Accuracy  |
|------------------------|-----------|
| Decision Tree          | 0.79    |
| Decision Tree + SMOTE  | 0.92    |
| Random Forest          | 0.80    |
| Random Forest + SMOTE  | 0.94    |

> SMOTE (Synthetic Minority Over-sampling Technique) helped improve model balance and performance.
