# Bank Term Deposit Prediction using Model Selection

## Overview

This project aims to predict whether a customer will subscribe to a term deposit based on demographic and banking information collected from previous marketing campaigns.

The objective is to help the bank improve future marketing strategies by identifying the factors that influence customer conversion and selecting the most effective machine learning model.

---

## Business Problem

A bank conducted marketing campaigns involving approximately 11,000 customers. Information such as age, occupation, marital status, education level, account balance, and loan status was collected.

The bank wants to:

* Identify factors influencing customer subscription to term deposits.
* Build predictive models to classify whether a customer will subscribe.
* Compare multiple machine learning algorithms and select the best-performing model.
* Improve future campaign effectiveness and customer targeting.

---

## Target Variable

**deposit**

* Yes → Customer subscribed to a term deposit.
* No → Customer did not subscribe.

---

## Dataset Features

The dataset includes:

* Age
* Job
* Marital Status
* Education
* Account Balance
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Marketing Outcome
* Deposit (Target Variable)

---

## Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Preprocessing
5. Model Building
6. Model Selection
7. Performance Evaluation

---

## Machine Learning Models Compared

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* K-Nearest Neighbors
* Support Vector Machine
* Naive Bayes
* AdaBoost Classifier

---

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC-AUC Score

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Structure

```
bank-term-deposit-prediction
│
├── data/
├── notebooks/
├── model_selection.ipynb
├── requirements.txt
├── README.md
└── images/
```

---

## Key Insights

* Identified important features affecting term deposit subscription.
* Compared multiple machine learning algorithms.
* Selected the model with the best predictive performance.
* Generated insights to support data-driven marketing decisions.

---

## Future Improvements

* Hyperparameter tuning using GridSearchCV.
* Cross-validation for robust evaluation.
* Feature importance analysis.
* Deployment using Streamlit or Flask.

---

## Author

**Deebesh Sundar**

Machine Learning & Data Science Practitioner
