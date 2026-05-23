# Explainable Hybrid Machine Learning Framework for Credit Card Fraud Detection Using Imbalanced Financial Transaction Data

## Project Overview

This project presents an advanced machine learning framework for detecting fraudulent credit card transactions using highly imbalanced financial transaction data.

The project focuses on:
- severe class imbalance handling
- explainable AI
- ensemble learning
- threshold optimization
- transaction-level fraud prediction
- business cost analysis
- anomaly detection
- risk-level classification

The final system combines multiple machine learning approaches into a hybrid ensemble framework to improve fraud detection performance while maintaining interpretability and practical usability.

---

# Research Question

How can explainable and cost-sensitive machine learning improve credit card fraud detection under severe class imbalance conditions?

---

# Dataset

## Dataset Name
Credit Card Fraud Detection Dataset

## Dataset Source
Kaggle

## Dataset Link
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

# Dataset Description

The dataset contains anonymized European credit card transactions made by cardholders over two days.

Key characteristics:
- 284,807 total transactions
- 492 fraudulent transactions
- highly imbalanced dataset
- PCA-transformed features (V1–V28)
- includes:
  - Time
  - Amount
  - Class (target variable)

Target labels:
- Class = 0 → Normal Transaction
- Class = 1 → Fraudulent Transaction

Fraudulent transactions represent approximately 0.172% of all transactions, making fraud detection significantly challenging.

---

# Machine Learning Models Used

## Baseline Model
- Logistic Regression

## Ensemble Models
- Random Forest
- Extra Trees

## Advanced Gradient Boosting Models
- LightGBM
- XGBoost
- CatBoost

## Anomaly Detection
- Isolation Forest

## Hybrid Ensemble
The final framework combines:
- LightGBM
- XGBoost
- CatBoost
- Random Forest
- Extra Trees

using weighted ensemble learning.

---

# Advanced Techniques Implemented

The project includes:
- SMOTE oversampling
- cost-sensitive learning
- threshold optimization
- SHAP explainability
- feature importance analysis
- permutation importance
- business cost analysis
- learning curve analysis
- runtime analysis
- cross-validation
- bootstrap confidence intervals
- transaction-level fraud testing
- risk-level classification
- anomaly detection

---

# Evaluation Metrics

The project evaluates model performance using:
- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- PR-AUC
- Confusion Matrix
- Matthews Correlation Coefficient (MCC)
- Balanced Accuracy
- Brier Score

PR-AUC is emphasized because the dataset is highly imbalanced.

---

# Explainable AI

The project integrates explainable AI techniques including:
- SHAP value analysis
- feature importance analysis
- permutation importance

These methods improve model transparency and interpretability.

---

# Business-Oriented Fraud Detection

The framework includes business-oriented fraud analysis by estimating:
- false positive costs
- false negative costs
- financial impact of fraud decisions

This improves practical applicability for real-world fraud monitoring systems.

---

# Real-World Fraud Testing

The notebook supports:
- individual transaction testing
- multiple transaction testing
- uploaded transaction file testing

The system outputs:
- fraud probability
- predicted class
- risk level
- recommended action

---

# Repository Contents

## Main Notebook
`Fraud_updated3.ipynb`

Contains:
- preprocessing
- model training
- evaluation
- explainability
- plotting
- fraud testing
- export system

## Project Outputs
`FINAL_INF612_FRAUD_PROJECT.zip`

Contains:
- generated figures
- CSV results
- trained models
- analysis outputs
- summaries

---

# How to Run

1. Open the notebook in Google Colab.
2. Upload `creditcard.csv` dataset when requested.
3. Run all notebook cells from top to bottom.
4. The notebook will:
   - preprocess data
   - train models
   - evaluate results
   - generate figures
   - save trained models
   - export results automatically

---

# Reproducibility

The notebook uses:
- fixed random seeds
- reproducible preprocessing
- reproducible train/test split
- automated export pipeline

All experiments can be reproduced directly from the notebook.

---

# Ethical AI Considerations

Fraud detection systems directly affect customers and financial institutions.

The project considers:
- false positive impacts on customers
- financial risk of missed fraud
- explainability and transparency
- responsible AI decision-making

The framework provides:
- fraud probability
- explainable outputs
- risk-level classification

instead of relying only on binary predictions.

---

# Limitations

Current limitations include:
- anonymized dataset features
- absence of real-time streaming data
- lack of customer behavioural history
- computational cost of ensemble learning

---

# Future Work

Future improvements may include:
- graph neural networks
- deep autoencoders
- transformer-based fraud detection
- real-time fraud streaming
- behavioural customer profiling
- interactive fraud dashboards

---

# Research Contribution

The main contribution of this project is an explainable hybrid fraud detection framework that combines:
- ensemble learning
- cost-sensitive learning
- threshold optimization
- anomaly detection
- explainable AI
- transaction-level fraud prediction

to improve fraud detection performance under severe class imbalance conditions.
