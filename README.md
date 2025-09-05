# Fraud-Detection-Using-Machine-Learning

📌 Project Overview

This project focuses on detecting fraudulent financial transactions using machine learning models. With over 6 million records and only 0.13% fraud cases, the dataset presents a significant class imbalance challenge. The goal is to build robust models that not only achieve high accuracy but also maximize recall (catching frauds) while minimizing false positives.

---

🔑 Key Highlights

Analyzed 6M+ financial transactions with severe class imbalance.
Performed data cleaning, feature engineering (day/hour extraction, behavioral ratios), and EDA to uncover fraud patterns.
Applied SMOTE to balance classes and improve fraud detection on minority class.
Built and compared multiple ML models: Logistic Regression, Random Forest, XGBoost, and LightGBM.
Evaluated models using Precision, Recall, F1-score, and ROC-AUC.
Achieved:
Logistic Regression: ~99% Recall, AUC ~0.9998
Random Forest: ~99% Precision & Recall, F1 ~99%, AUC ~0.9988
XGBoost & LightGBM: High overall performance with strong fraud detection.

Identified key fraud indicators such as missing balances, high-value transfers, and emptied accounts, providing actionable prevention strategies.

---

🛠️ Tech Stack

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-Learn, Imbalanced-Learn, XGBoost, LightGBM, Matplotlib, Seaborn

Techniques: Data Cleaning, Feature Engineering, SMOTE, Model Evaluation, Feature Importance


