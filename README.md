# Credit Card Fraud Detection Model

## Overview
This project aims to build a machine learning model that predicts whether a given credit card transaction is fraudulent or not. The dataset used is the **Credit Card Fraud Detection Dataset** containing detailed transaction data.

## Dataset Details
- **Source:** Kaggle Credit Card Fraud Detection Dataset
- **Total Records:** 555,719
- **Features:** 23 columns including `amt`, `category`, `city_pop`, etc.
- **Target Variable:** `is_fraud` (1 = Fraud, 0 = Not Fraud)

## Project Workflow
1. **Data Loading and Preprocessing**
   - Dropped irrelevant columns (`Unnamed: 0`, `first`, `last`, etc.)
   - Encoded categorical features using `pd.get_dummies()`
   - Handled class imbalance using **RandomUnderSampler**

2. **Model Training**
   - Models used:
     - **RandomForestClassifier**
     - **XGBoostClassifier**
     - **GradientBoostingClassifier**

3. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1 Score
   - Confusion Matrix

4. **User Input Prediction**
   - Interactive console-based input where the user enters transaction details.
   - The model predicts if the transaction is **Fraudulent** or **Not Fraudulent**.



## Usage
- Enter transaction details when prompted.
- The model will output whether the transaction is **Fraudulent** or **Not Fraudulent**.

## Future Improvements
- Implement advanced feature engineering.
- Enhance model performance using hyperparameter tuning.
- Integrate with a web API for better usability.

## Author
**Tina** - MSc Data Science and Analytics Student at Jain University

