# Data-Mining-Project

## Project Overview

This project applies machine learning techniques to predict loan approval status based on applicant information. The analysis is based on a dataset sourced from Kaggle, aiming to assist financial institutions in automating the loan eligibility process and making data-driven decisions.

## Dataset

The dataset contains information about applicants including demographics, income, employment, loan details, and loan approval status.

    Target Variable: Loan_Status

    Key Features:

      Gender, Married, Dependents, Education, Self_Employed

      ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term

      Credit_History, Property_Area

## Data Preparation

    Handled missing values with mode and median imputation

    Dropped irrelevant features (Loan_ID)

    Cleaned dataset for modeling

## Exploratory Data Analysis

    Summary statistics with describe() and info()

    Null value analysis

    Visualized data with AutoViz

## Modeling Approach

Used PyCaret to streamline the machine learning pipeline.

    Compared models: Random Forest and XGBoost

    Selected Random Forest as the final model for its superior performance in:

        Accuracy: 0.7904

        Precision: 0.7935

        F1-score: 0.7717

## Feature Importance

    Credit_History (most influential)

    LoanAmount

    ApplicantIncome

## Tools & Libraries

    Python

    Pandas

    PyCaret

    AutoViz

    Jupyter Notebook / Google Colab
