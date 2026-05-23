# 💳 Credit Card Fraud Detection

## 📌 Overview
Detecting fraudulent credit card transactions using Machine Learning with imbalanced data handling.

## 📊 Dataset
- **Source:** Kaggle — Credit Card Fraud Detection (MLG-ULB)
- **Size:** 11,959 rows, 31 columns
- **Fraud cases:** 52 (0.4%) — Highly imbalanced!
- **Target:** Class (0 = Normal, 1 = Fraud)

## 🔧 Steps Performed
1. Exploratory Data Analysis (EDA)
2. Handling Missing Values — Filled with median
3. Handling Imbalanced Data — SMOTE (oversampling)
4. Model Training — Random Forest Classifier
5. Comparison — With vs Without SMOTE

## 🤖 Model Used
- Random Forest Classifier
- SMOTE for handling class imbalance

## 📈 Results
| | Without SMOTE | With SMOTE |
|--|--|--|
| Fraud Precision | 1.00 | 0.69 |
| Fraud Recall | 0.90 | 0.90 |
| Fraud F1 | 0.95 | 0.78 |
| Overall Accuracy | 100% | 100% |

## 💡 Key Learnings
- SMOTE helps with recall but may reduce precision on small datasets
- Imbalanced datasets need special handling
- Accuracy alone is not a good metric for fraud detection

## 📦 Libraries Used
```python
pandas, numpy, matplotlib, seaborn
sklearn, imblearn
```

## 🗂️ Files
- `Credit_Card_Fraud_Detection.ipynb` — Main notebook
