# Customer_chrun_prediction1
# 📊 Customer Churn Prediction using Machine Learning

## 🔍 Problem Statement
Telecom companies lose revenue due to customer churn. The goal of this project is to build a model that predicts whether a customer will leave the service, based on historical usage and subscription data.

## 🎯 Objective
To predict customer churn and identify the features that most influence customer behavior using machine learning models.

## 📁 Dataset
- **Source**: [Mention dataset source or link]
- **Total Records**: 7043
- **Target Column**: `Churn` (Yes or No)
- **Features**: Customer demographics, account details, service usage, etc.

## 🔧 Data Preprocessing
- Missing value handling
- Encoding categorical variables using One-Hot Encoding
- Feature scaling (if needed)
- Train-test split (80-20)

## 🤖 ML Models Used
- Logistic Regression
- Decision Tree Classifier
- ✅ **Random Forest Classifier (Best performing)**

## 🧪 Model Evaluation
Best Model: **Random Forest**
- **Accuracy**: 78%
- **F1 Score**: 0.849
- **Precision**: 0.86 (Class 0), 0.57 (Class 1)
- **Recall**: 0.83 (Class 0), 0.62 (Class 1)

## 🏆 Best Hyperparameters
```json
{
  "n_estimators": 100,
  "min_samples_split": 2,
  "min_samples_leaf": 2,
  "max_depth": null
}
