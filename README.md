# CreditCardApproval

## Project Overview
The **CreditCardApproval** project aims to develop a robust model for predicting credit card approvals using logistic regression. This project involves comprehensive data preprocessing, exploratory data analysis, and model tuning to achieve optimal performance.

---

## 1. Cleaning Data

- The dataset was downloaded from the UCI ML Repository and missing values (`?`) replaced by `NaN`.
- Numerical columns with missing values were filled with the mean, and categorical columns were filled with the mode.
- Data types were corrected where necessary (e.g., `Age` and `ZipCode` converted to `float64`).
- Column names were replaced with meaningful labels (e.g., `0 -> Gender`, `1 -> Age`).
- The dataset was verified to have no remaining missing values, making it ready for transformation.

---

## 2. Univariate Analysis
A detailed examination of individual variables to understand their distributions:
- Visualizations such as histograms, box plots, and density plots.
- Statistical measures like mean, median, standard deviation, skewness, and kurtosis.
- Identification of data abnormalities or outliers.

---

## 3. Bivariate Analysis
Analysis of relationships between pairs of variables:
- Scatter plots and line plots for numerical variables.
- Heatmaps and grouped bar charts for categorical vs numerical comparisons.
- Statistical tests (e.g., chi-square, t-tests) for measuring relationships.

---

## 4. Correlation
Investigating the correlations among numerical features:
- Calculating the Pearson or Spearman correlation coefficients.
- Visualizing correlations using a heatmap to identify multicollinearity or relationships.
- Evaluating the implications of strong correlations on feature selection.

---

## 5. Logistic Regression
Building a logistic regression model to predict credit card approvals:
- Splitting the dataset into training and testing sets.
- Training the model using the logistic regression algorithm.
- Evaluating performance using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

---

## 6. Model Tuning Using Grid Search
Optimizing the model through hyperparameter tuning:
- Defining a grid of hyperparameters such as penalty types (L1, L2) and regularization strengths.
- Using cross-validation to evaluate different parameter combinations.
- Selecting the best combination for improved model performance.

---

## 7. Feature Selection
Reducing dimensionality to improve model interpretability and performance:
- Identifying important features using methods like Recursive Feature Elimination (RFE) or model coefficients.
- Eliminating redundant or irrelevant features based on correlation analysis and domain knowledge.
- Re-training the model with the selected features and evaluating its performance.

---
