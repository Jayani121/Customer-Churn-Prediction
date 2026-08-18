# Customer Churn Prediction using Machine Learning

A machine learning project that predicts whether a customer is likely to churn using customer demographic and service-related information.

## Project Overview

Customer churn is an important business problem because losing existing customers can negatively affect revenue and long-term customer relationships.

This project develops and compares two machine learning classification models:

- Logistic Regression
- Random Forest Classifier

The models are evaluated using Accuracy, Precision, Recall, F1-Score, ROC-AUC, and Confusion Matrix.

---

##  Objectives

- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess customer data
- Analyze customer churn patterns
- Build machine learning classification models
- Compare Logistic Regression and Random Forest
- Evaluate model performance using multiple metrics
- Identify important features
- Generate business-oriented insights

---

##  Exploratory Data Analysis

The dataset was explored to understand customer characteristics and churn patterns.

Key analysis included:

- Churn distribution
- Numerical feature analysis
- Categorical feature analysis
- Data quality checks
- Class distribution
- Relationships between customer characteristics and churn

### Churn Distribution

![Churn Distribution](images/churn_distribution.png)

---

##  Data Preprocessing

The following preprocessing steps were performed:

- Missing value analysis
- Duplicate record checking
- Data type validation
- Categorical variable encoding
- Numerical feature processing
- Feature-target separation
- Train-test split
- Feature scaling where required
- Class weighting for Random Forest

---

##  Machine Learning Models

### Logistic Regression

Logistic Regression was used as the baseline classification model.

### Random Forest

Random Forest was implemented as an ensemble learning model using:

```text
n_estimators = 200
random_state = 42
class_weight = balanced
