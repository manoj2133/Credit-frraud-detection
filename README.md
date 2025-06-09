
# 🛡️ Credit Card Fraud Detection

## 📌 Objective
To develop a machine learning system that identifies fraudulent credit card transactions with high accuracy, especially in the presence of severe class imbalance.

## 📊 Dataset
- **Source**: Credit card transactions dataset (likely from Kaggle)
- **Features**:
  - `Time`, `Amount`: Basic transaction details
  - `V1` to `V28`: PCA-anonymized features
  - `Class`: 0 (non-fraud) or 1 (fraud)

## 🔍 Exploratory Data Analysis (EDA)
- Visualized class imbalance
- Checked correlation between features
- Analyzed transaction amount patterns for fraud vs. non-fraud

## 🧹 Preprocessing
- Scaled `Amount` and `Time`
- Addressed class imbalance using:
  - Random Undersampling
  - SMOTE (Synthetic Minority Over-sampling Technique)
- Train-Test split for model validation

## 🤖 Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Support Vector Classifier
- K-Nearest Neighbors

## 📏 Evaluation Metrics
- Accuracy (limited use due to imbalance)
- Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score

## ✅ Best Performing Model
_(To be filled in by user)_  
Example: `XGBoost` achieved a **ROC-AUC Score of 0.98** with high precision on the fraud class.

## 📁 Project Structure
```
credit-fraud-detection/
├── credit_fraud_detection project.ipynb   # Main Jupyter notebook
├── data/                                  # Raw and processed data (if applicable)
└── README.md                              # Project overview
```

## 🚀 Future Work
- Real-time detection API using FastAPI or Flask
- Unsupervised anomaly detection models (e.g., Autoencoders)
- Explainable AI with SHAP

## 🙌 Credits
- Dataset from ULB (Université Libre de Bruxelles)
- Tools: pandas, numpy, sklearn, seaborn, matplotlib, xgboost
