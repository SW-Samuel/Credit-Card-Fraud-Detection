# Credit Card Fraud Detection 💳🚨

This project focuses on detecting fraudulent credit card transactions using a real-world dataset with anonymized features.

## 📌 Project Overview

The notebook contains a full pipeline for fraud detection, covering:

### 📊 Exploratory Data Analysis (EDA)
- Understanding the distribution between normal and fraudulent transactions.
- Analyzing class imbalance and its impact on modeling.

### 🧹 Data Preprocessing
- Feature scaling to standardize the input variables.
- Handling imbalanced data using techniques like **SMOTE** (Synthetic Minority Over-sampling Technique).

### 🤖 Machine Learning Modeling
- Building and evaluating classification models such as:
  - **Logistic Regression**
  - **Random Forest**

### 📈 Performance Evaluation
- Using multiple metrics to assess model performance:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
  - ROC-AUC Curve

---

## 📂 Dataset

- 🏢 **Source:** [Dataset Credit Card](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data)
- **Description:** Contains European credit card transactions over two days in 2013, with 492 frauds out of 284,807 transactions.

## ⚙️ Technologies Used

- Python 🐍  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Seaborn  
- Imbalanced-learn (SMOTE)  

## 🚀 Results

After data balancing and applying classification models, the project achieved improved Recall and Precision in fraud detection, addressing the dataset's heavy class imbalance.

## 📢 Author

SW Samuel
