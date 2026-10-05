# Credit Scoring Model

## 📌 Project Overview

This project was developed as part of my **Alpha Internship** to build a machine learning model that predicts an individual's **creditworthiness** based on financial information.

The project uses classification algorithms to determine whether an applicant is likely to be **Creditworthy** or **Not Creditworthy**.

Two machine learning algorithms were implemented:

* Logistic Regression
* Random Forest Classifier

The models were evaluated using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

---

## 🎯 Objective

The main objective of this project is to develop a machine learning-based credit scoring system that can predict an individual's creditworthiness using financial features such as:

* Income
* Debt
* Payment History
* Credit Utilization
* Debt-to-Income Ratio

---

## 📊 Dataset

For this educational project, a **sample financial dataset** was created to demonstrate the complete machine learning workflow.

The dataset contains financial information and a target variable:

| Feature            | Description                                              |
| ------------------ | -------------------------------------------------------- |
| Income             | Monthly income of the individual                         |
| Debt               | Existing debt                                            |
| Payment_History    | Payment history (1 = Good, 0 = Poor)                     |
| Credit_Utilization | Percentage of available credit being used                |
| Debt_to_Income     | Ratio of debt to income                                  |
| Creditworthy       | Target variable (1 = Creditworthy, 0 = Not Creditworthy) |

**Dataset size:** 20 records

> Note: The dataset is intended for educational demonstration and should not be used for real-world financial or lending decisions.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Joblib

---

## 🤖 Machine Learning Algorithms

### 1. Logistic Regression

Logistic Regression was used as the first classification algorithm to predict the probability of an individual being creditworthy.

### 2. Random Forest

Random Forest Classifier was implemented as a second model to compare its performance with Logistic Regression and to analyze feature importance.

---

## ⚙️ Methodology

The project follows these steps:

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
Data Visualization
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Random Forest
      ↓
Model Prediction
      ↓
Model Evaluation
      ↓
Model Comparison
      ↓
New Applicant Prediction
```

---

## 🔧 Feature Engineering

A new feature called **Debt-to-Income Ratio** was created.

### Formula

```text
Debt-to-Income Ratio = Debt / Income
```

This feature provides an additional indication of an individual's financial burden relative to their income.

---

## 📈 Model Evaluation

The models were evaluated using the following metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

A **Confusion Matrix** and **ROC Curve** were also created to visualize model performance.

Since the project uses a small educational dataset, the evaluation results should not be interpreted as real-world model performance.

---

## 🔍 Feature Importance

The Random Forest model was used to analyze the importance of different financial features.

This helps identify which financial factors contribute more strongly to the model's predictions.

---

## 👤 New Applicant Prediction

The trained model was also tested using a new applicant's financial information.

The system takes values such as:

```text
Income
Debt
Payment History
Credit Utilization
Debt-to-Income Ratio
```

and predicts:

```text
Creditwort
```
