# Loan Payback Prediction Using Machine Learning

## 📌 Project Overview

This project involves building a simple machine learning classification model to predict whether a customer will **repay a loan or default**. The workflow covers data preprocessing, model training, evaluation, and insights derivation using a small loan payback dataset.

## 🎯 Objective

To predict loan repayment behavior using machine learning techniques and evaluate model performance using accuracy, confusion matrix, and feature importance.

## 🛠️ Tools Used

- **Python**
- **pandas**
- **scikit-learn**
- **matplotlib**
- **Jupyter Notebook**

## 📊 Approach

1. **Data Loading & Exploration**
   - Loaded the dataset using pandas
   - Performed Exploratory Data Analysis (EDA) including value counts, histograms, and pie charts

2. **Data Preprocessing**
   - Checked for missing values
   - Encoded categorical features
   - Scaled numerical features

3. **Model Training**
   - Split data into train/test sets (80/20)
   - Trained the following models:
     - XGBoost
     - Random Forest Classifier
     - LightGBM

4. **Evaluation**
   - Used accuracy and confusion matrix for performance assessment
   - Visualized results with confusion matrix heatmaps
   - Analyzed feature importance

## 📈 Results

### Model Accuracy
- **XGBoost**: 90.12%
- **Random Forest**: 90.12%
- **LightGBM**: 90.81% (*best performing*)

### Key Findings
- Models performed well on the majority class
- Some misclassification of defaults — typical for financial datasets
- Confusion matrix provided deeper insights beyond accuracy

## 🧠 Learnings

- Encoding and scaling significantly impact model accuracy
- Tree-based models handle mixed data types better than linear models
- Loan datasets often suffer from class imbalance, affecting predictions
- Confusion matrix offers more insight than accuracy alone

## 🔮 Future Improvements

- Handle class imbalance using **SMOTE**
- Perform **hyperparameter tuning** for better accuracy
- Build a **Streamlit dashboard** for interactive predictions

## 📁 Repository

🔗 [GitHub Link](https://github.com/mohitrohda/Converse_Assessment_)

---

*This project was developed as part of a machine learning assessment.*