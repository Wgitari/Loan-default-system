# Loan_Defaulter_System

This project aims to predict loan defaults using machine learning models, focusing on Logistic Regression, Decision Tree Classifier, and Random Forest Classifier.

## Data Preprocessing

Missing Values: Handled by converting numeric columns to NaN and applying imputation techniques.
Categorical Encoding: The target variable default was label encoded to convert categorical data to numeric.
Feature Scaling: Numerical features were normalized using StandardScaler.
Class Imbalance: The dataset was balanced using SMOTE (Synthetic Minority Over-sampling Technique).

## Models Evaluated

### Logistic Regression:

Accuracy: 0.753, Precision: 0.917, Recall: 0.753, F1-score: 0.827
Suitable for simple classification tasks but less effective in capturing defaults.

### Decision Tree:

Accuracy: 0.810, Precision: 0.907, Recall: 0.844, F1-score: 0.875
Performs well but can overfit and may not generalize well.

### Random Forest:

Accuracy: 0.845, Precision: 0.918, Recall: 0.881, F1-score: 0.899
Best overall performance, balancing accuracy and recall.

## Conclusion

Random Forest emerged as the best model with the highest recall and F1-score, making it ideal for detecting defaults. It outperformed Logistic Regression and Decision Tree in terms of overall performance and generalization.