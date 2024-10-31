# HomeWork4ML
Data Analysis and Model Comparison: Breast Cancer Classification and Housing Price Prediction

# Data Analysis and Model Comparison: Breast Cancer Classification and Housing Price Prediction

## Table of Contents
- [Problem 1: Breast Cancer Classification Using SVM and PCA](#problem-1-breast-cancer-classification-using-svm-and-pca)
  - [Overview](#overview)
  - [Key Steps](#key-steps)
  - [Graphical Visualization](#graphical-visualization)
  - [Conclusion](#conclusion)
- [Problem 2: Housing Price Prediction Using Regression Models](#problem-2-housing-price-prediction-using-regression-models)
  - [Overview](#overview-1)
  - [Key Steps](#key-steps-1)
  - [Graphical Comparison](#graphical-comparison)
  - [Conclusion](#conclusion-1)

---

## Problem 1: Breast Cancer Classification Using SVM and PCA

### Overview
This analysis focuses on classifying breast cancer data using Support Vector Machines (SVM) enhanced by Principal Component Analysis (PCA). The dataset is prepared by splitting it into training and testing sets and scaling the features.

### Key Steps
1. **Data Preparation**: 
   - The breast cancer dataset is loaded.
   - Features are standardized using `StandardScaler()`.

2. **Model Evaluation**: 
   - A function evaluates model performance using accuracy, precision, and recall.

3. **Optimal Number of Principal Components**:
   - PCA is applied to reduce dimensionality.
   - An SVM classifier is trained and evaluated across different numbers of components.

4. **Kernel Comparison**:
   - Various SVM kernels are tested to find the best performing model.

5. **Logistic Regression Comparison**:
   - A Logistic Regression model is compared with the best SVM model.

### Graphical Visualization
*(Insert graphs here)*

### Conclusion
The study highlights the benefits of PCA in improving SVM classification performance, providing insights through comparative analysis.

---

## Problem 2: Housing Price Prediction Using Regression Models

### Overview
This analysis aims to predict housing prices using various regression models, leveraging PCA for dimensionality reduction.

### Key Steps
1. **Data Preparation**: 
   - A synthetic housing dataset is generated.
   - Categorical features are encoded.
   - Data is split into training and testing sets and standardized.

2. **Enhanced Model Evaluation**: 
   - A function calculates RMSE, MAE, and R² score for model performance evaluation.

3. **PCA Analysis**:
   - PCA is performed to assess its impact on regression model performance.
   - An SVR model is trained and evaluated.

4. **Kernel Comparison**:
   - Various SVR kernels are evaluated using cross-validation to identify the best kernel.

5. **Regularized Regression Models Comparison**:
   - The performance of Ridge, Lasso, and ElasticNet models is compared against the best SVR model.

### Graphical Comparison
*(Insert graphs here)*

### Conclusion
The analysis demonstrates the effectiveness of PCA in enhancing regression model performance and provides a comparative perspective on different regression techniques for housing price prediction.

---
