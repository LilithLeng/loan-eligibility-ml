# Loan Eligibility Prediction using Machine Learning

This project builds a machine learning model to predict whether a loan application should be approved based on applicant financial and demographic information.

The goal is to help financial institutions automate part of the loan approval process and identify applicants who are more likely to qualify for loans.

The project demonstrates a full machine learning workflow including data preprocessing, feature engineering, model training, and performance evaluation.

---

# Project Overview

Loan approval decisions are critical for financial institutions. Approving high-risk borrowers may lead to financial loss, while rejecting qualified applicants may reduce business opportunities.

Machine learning models can assist lenders by identifying patterns in historical loan data and predicting the likelihood that an applicant will qualify for a loan.

This project develops predictive models to estimate loan eligibility using applicant attributes such as income, credit history, employment status, and loan characteristics.

---

# Business Problem

Financial institutions must evaluate large numbers of loan applications. Manual evaluation can be slow and inconsistent.

Key questions addressed in this project include:

- Which factors influence loan approval decisions?
- Can machine learning models accurately predict loan eligibility?
- Which model performs better for this classification task?

The goal is to build a predictive model that helps lenders make faster and more consistent decisions.

---

# Dataset

The dataset contains loan application records including demographic and financial information.

Each row represents a loan applicant.

Key features include:

- **Gender** — applicant gender
- **Married** — marital status
- **Dependents** — number of dependents
- **Education** — education level
- **Self_Employed** — employment type
- **ApplicantIncome** — applicant income
- **CoapplicantIncome** — co-applicant income
- **LoanAmount** — loan amount requested
- **Loan_Amount_Term** — loan repayment period
- **Credit_History** — applicant credit history
- **Property_Area** — location type
- **Loan_Status** — loan approval outcome (target variable)

---

# Tools & Technologies

The analysis and modeling were conducted using **Python**.

Main libraries used:

- **Pandas** — data cleaning and transformation
- **NumPy** — numerical operations
- **Matplotlib / Seaborn** — data visualization
- **Scikit-learn** — machine learning models and evaluation

The project was implemented in **Jupyter Notebook**.

---

# Machine Learning Workflow

The project follows a typical machine learning pipeline.

---

## 1. Data Exploration

Initial data exploration was conducted to understand:

- feature distributions
- missing values
- relationships between variables
- class balance of the target variable

---

## 2. Data Preprocessing

Several preprocessing steps were performed:

- handling missing values
- encoding categorical variables
- feature transformation
- scaling where necessary

Feature engineering was applied to improve model performance.

---

## 3. Model Training

Two machine learning models were trained:

### Logistic Regression

Logistic regression is a widely used classification algorithm that estimates the probability of a binary outcome.

### Random Forest

Random Forest is an ensemble learning method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 4. Model Evaluation

Model performance was evaluated using:

- accuracy score
- confusion matrix
- classification metrics

Comparing multiple models helps identify the best-performing approach.

---

# Key Insights

The analysis shows that several factors strongly influence loan approval decisions.

Credit history is one of the most important predictors of loan eligibility.

Income level and loan amount also play an important role in determining whether a loan application is approved.

Machine learning models such as Random Forest can capture complex relationships between applicant features and approval outcomes.
