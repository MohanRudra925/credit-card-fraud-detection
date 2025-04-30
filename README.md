# Credit Card Fraud Detection using Logistic Regression

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using the **Logistic Regression** algorithm. Credit card fraud is a growing concern in the financial industry, and this project aims to create a machine learning-based system that can effectively identify suspicious transactions and help prevent financial losses.

The dataset used in this project is highly imbalanced, with only a small percentage of transactions classified as fraudulent. The model is trained to accurately distinguish between genuine and fraudulent transactions, even with this imbalance.

---

## 🧠 Machine Learning Model

- **Algorithm Used:** Logistic Regression
- **Problem Type:** Binary Classification
- **Libraries Used:** `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`

---

## 🔍 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Description:**
  - Contains 284,807 transactions
  - 492 frauds (only ~0.172%)
  - Features are numerical and result of PCA transformation (except Time and Amount)

---

## ⚙️ Steps Performed

1. **Data Preprocessing**
   - Handled missing/null values
   - Scaled features using StandardScaler
   - Explored class imbalance

2. **Model Training**
   - Split data into training and testing sets
   - Trained Logistic Regression on the dataset

3. **Evaluation Metrics**
   - AUC Score

4. **Handling Class Imbalance**
   - Used under-sampling to balance the dataset for better model training

---

## 📈 Model Performance

- **Precision:** High precision to minimize false positives
- **Recall:** Optimized to ensure most frauds are detected
- **AUC Score:** Evaluated using ROC curve to assess model capability

> The model showed good performance in detecting fraudulent transactions while maintaining a low false positive rate.
