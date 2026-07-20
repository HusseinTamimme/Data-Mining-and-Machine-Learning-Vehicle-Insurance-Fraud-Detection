# 🚗 Vehicle Insurance Fraud Detection Engine

An end-to-end Machine Learning project that detects fraudulent vehicle insurance claims using data preprocessing, feature engineering, feature selection, class imbalance handling, and multiple machine learning models.

The project focuses on building a robust and unbiased fraud detection pipeline by comparing different preprocessing and modeling strategies instead of relying on a single algorithm.

---

## 📌 Project Overview

Insurance fraud costs companies billions of dollars every year. Detecting fraudulent claims manually is expensive and time-consuming.

This project develops a complete fraud detection pipeline capable of identifying suspicious insurance claims while minimizing bias and improving prediction reliability.

The workflow includes:

* Data exploration
* Missing value handling
* Feature engineering
* Data preprocessing
* Feature selection
* Class imbalance handling
* Model training
* Performance evaluation
* Error analysis

---

## 🚀 Features

* Exploratory Data Analysis (EDA)
* Missing value analysis
* KNN Imputation for numerical features
* Mode imputation for categorical features
* Min-Max Normalization
* One-Hot Encoding
* Binary Feature Mapping
* Feature Selection using three different techniques
* Multiple class imbalance solutions
* Comparison of several Machine Learning models
* Detailed evaluation metrics
* Confusion Matrix analysis

---

## 🛠 Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE, Tomek Links)

---

## 📂 Project Workflow

```text
Dataset
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Missing Value Handling
   │
   ▼
Normalization
   │
   ▼
Categorical Encoding
   │
   ▼
Feature Selection
   │
   ▼
Dataset Balancing
   │
   ▼
Model Training
   │
   ▼
Evaluation
   │
   ▼
Model Comparison
```

---

# 📊 Data Preprocessing

The preprocessing pipeline includes:

### Missing Values

* KNN Imputer (Numerical Features)
* Simple Imputer using Most Frequent (Categorical Features)

### Scaling

* Min-Max Scaler

### Encoding

* One-Hot Encoding
* Binary Mapping (Yes/No → 1/0)

### Dataset Split

* Train/Test Split
* Stratified Sampling

---

# 🎯 Feature Selection

Three different feature selection approaches were evaluated.

## 1. SelectKBest

* Chi-Square Test
* Top 22 Features

## 2. Random Forest Feature Importance

* SelectFromModel
* Median Threshold

## 3. XGBoost Feature Importance

* Mean Importance Threshold

---

# ⚖ Handling Class Imbalance

The project compares three balancing techniques.

* SMOTE
* Tomek Links
* SMOTE + Tomek

This resulted in multiple balanced datasets used for experimentation.

---

# 🤖 Machine Learning Models

The following models were trained and evaluated:

* Random Forest Classifier
* XGBoost Classifier
* Multi-Layer Perceptron (MLP)

Each model was tested across multiple combinations of:

* Feature Selection
* Balancing Technique

to identify the most reliable pipeline.

---

# 📈 Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* False Positive Rate
* False Negative Rate

---

# 🏆 Results

The experiments showed that:

* Random Forest provided the best balance between prediction accuracy and class bias.
* XGBoost achieved very high accuracy but tended to favor the majority class on some dataset variations.
* Comparing multiple preprocessing strategies significantly improved the overall understanding of model behavior.

---

---

# 💡 Key Learning Outcomes

Through this project I gained hands-on experience with:

* End-to-End Machine Learning Pipelines
* Data Cleaning
* Feature Engineering
* Class Imbalance Handling
* Model Evaluation
* Feature Selection
* Machine Learning Model Comparison
* Building reproducible workflows

---

# 🔮 Future Improvements

* Hyperparameter Optimization
* Explainable AI (SHAP/LIME)
* Model Deployment using Streamlit
* REST API Integration
* Real-Time Fraud Detection
* Deep Learning Experiments

---

# 👨‍💻 Author

**Hussein Tamimme**

LinkedIn:
https://www.linkedin.com/in/hussein-tamimme-1943072a5/

GitHub:
https://github.com/HusseinTamimme

---

## ⭐ If you found this project useful, consider giving it a star!
