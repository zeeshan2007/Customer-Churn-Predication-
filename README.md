# 📉 Customer Churn Prediction

A Machine Learning classification project that predicts whether a customer is likely to churn based on customer demographics, account information, and subscribed services.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses. This project uses Machine Learning to identify customers who are likely to leave the service, helping businesses improve customer retention strategies.

---

## 🚀 Features

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Multiple Classification Models
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization using Pickle

---

## 📊 Dataset

**Dataset:** Telco Customer Churn Dataset

### Target Variable

- **Churn**
  - Yes → Customer left
  - No → Customer stayed

---

## 🛠️ Data Preprocessing

- Removed Customer ID
- Converted TotalCharges to numeric
- Handled missing values
- Encoded categorical variables
- Applied StandardScaler
- Split data into Training & Testing sets

---

## 🤖 Machine Learning Models

The following classification algorithms were evaluated:

- Logistic Regression ✅
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
- XGBoost

---

## 🏆 Final Model

**Logistic Regression** achieved the best overall performance and was selected as the final model.

### Final Performance

| Metric | Score |
|---------|------:|
| Accuracy | **80.38%** |
| Precision | **64.76%** |
| Recall | **57.49%** |
| F1 Score | **60.91%** |
| ROC-AUC | **73.08%** |

---

## 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── customer_churn_raw.csv
├── customer_churn_cleaned.csv
├── customer_churn_model.pkl
├── scaler.pkl
├── columns.pkl
├── Customer_Churn.ipynb
└── README.md
```

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- Joblib

---

## 📈 Workflow

```
Raw Data
    │
    ▼
Data Cleaning
    │
    ▼
EDA
    │
    ▼
Feature Engineering
    │
    ▼
Train-Test Split
    │
    ▼
StandardScaler
    │
    ▼
Model Training
    │
    ▼
Model Evaluation
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Final Model
    │
    ▼
Pickle Files
```

---

## 💾 Saved Files

- `customer_churn_model.pkl`
- `scaler.pkl`
- `columns.pkl`

These files can be directly used to deploy the model in a web application.

---

## 📬 Author

**Zeeshan Shaukat**

GitHub: https://github.com/zeeshan2007

---

⭐ If you found this project useful, consider giving it a star.
