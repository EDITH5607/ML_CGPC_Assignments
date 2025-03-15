# Machine Learning Assignments

This repository contains solutions to various machine learning problems, focusing on **linear regression, polynomial regression, logistic regression, gradient descent**, and model evaluation.

## 📌 Assignment Overview

### **1️⃣ Linear & Polynomial Regression**
- **Dataset:**
  - Given dataset with `x` and `y` values.
- **Tasks:**
  - Fit **Linear Regression**.
  - Fit **Polynomial Regression** (degree 2 and 3).
  - Compare models using:
    - **Sum of Squared Errors (SSE)**
    - **R² (coefficient of determination)**.

### **2️⃣ Custom Implementation of Regression**
- **Tasks:**
  - Implement regression coefficients calculation manually using:
    \[
    \alpha = (X^T X)^{-1} X^T Y
    \]
  - Compute **SSE**:
    \[
    SSE = \sum_{i=1}^{m} (y_i - \hat{y}_i)^2
    \]
  - Compute **R²**:
    \[
    R^2 = 1 - \frac{SSE}{SST}
    \]

### **3️⃣ Logistic Regression on Pima Dataset**
- **Dataset:**
  - Download the **Pima Diabetes Dataset** from Kaggle.
- **Tasks:**
  - Build a **Logistic Regression** classifier to predict diabetes.
  - Vary the **Training-Testing Split**:  
    - (80% Training, 20% Testing)  
    - (70% Training, 30% Testing)  
    - (60% Training, 40% Testing)  
  - Analyze model performance across different splits.

### **4️⃣ Bias-Variance Analysis**
- **Dataset:**
  - Download **Position-Salaries Dataset** from Kaggle.
- **Tasks:**
  - Fit **Linear Regression**.
  - Fit **Polynomial Regression** (degrees 2, 5, 11).
  - Compute **Bias & Variance** using `mixtend` module.
  - Discuss **Underfitting vs. Overfitting**.

### **5️⃣ Gradient Descent for Linear Regression**
- **Tasks:**
  - Implement **Gradient Descent** from scratch.
  - Estimate regression coefficients.
  - Compare results with the analytical method.

## 📂 Folder Structure
