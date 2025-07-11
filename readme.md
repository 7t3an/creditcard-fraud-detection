# 🛡️ Credit Card Fraud Detection

This project applies machine learning to detect fraudulent credit card transactions using the XGBoost classifier and the CreditCard dataset from Kaggle.

## 🚀 Dataset
- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Features: 28 anonymized PCA components, `Time`, `Amount`
- Target: `Class` (1 = fraud, 0 = legitimate)

## 🧠 Model
- **Pipeline**: StandardScaler + XGBoost
- **Class imbalance** handled with `scale_pos_weight`

## 📊 Metrics (Test Set)
- **Accuracy**: 0.9997
- **Precision**: 0.92
- **Recall**: 0.88
- **F1 Score**: 0.90
- **ROC AUC**: 0.98
- **PR AUC**: 0.86

## 📦 Libraries Used
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- xgboost
- kagglehub
- jupyterlab

## 🧪 How to Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/creditcard-fraud-detection.git
cd creditcard-fraud-detection
