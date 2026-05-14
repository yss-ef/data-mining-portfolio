# Lab 04: Bank Marketing — Binary Classification Analysis

## Overview
This laboratory focuses on building and evaluating machine learning models to predict whether a client will subscribe to a term deposit (variable `y`) based on a marketing campaign dataset. It follows a complete ML pipeline from exploratory data analysis to model performance comparison.

## Key Technical Tasks
*   **Exploratory Data Analysis (EDA)**: Investigating feature distributions and relationship with the target variable.
*   **Data Preprocessing**: 
    *   Handled "unknown" values by imputing with the mode.
    *   Binary encoding for the target variable.
    *   One-Hot Encoding for categorical features.
    *   Standard scaling for numerical features.
*   **Model Implementation**:
    *   **Logistic Regression**: Used as a baseline classifier.
    *   **Decision Tree**: Exploring non-linear patterns.
    *   **Random Forest**: Leveraging ensemble learning for improved robustness.
*   **Performance Evaluation**: Utilizing Recall, F1-Score, and Confusion Matrices to prioritize identifying potential subscribers.

## Analytical Findings
*   **Class Imbalance**: Identified that the dataset is imbalanced, requiring careful metric selection (F1 over Accuracy).
*   **Key Predictors**: Duration of the call and previous campaign outcomes were significant indicators of success.
*   **Model Comparison**: The Random Forest model generally provided the best balance between precision and recall for this specific task.

## Dataset
*   `bank-marketing.csv`: Dataset containing 4,119 records with 20 features related to client demographics, social-economic indicators, and campaign contact history.

---
*Developed for the Data Mining Module - Mundiapolis University.*

Authored by Youssef Fellah.  
Developed for the Engineering Cycle - Mundiapolis University.
