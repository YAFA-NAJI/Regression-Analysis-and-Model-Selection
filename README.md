# Car Price Prediction using Regression Models

## Project Overview
This project focuses on building, evaluating, and optimizing regression models to predict car prices using the YallaMotors dataset. The goal is to apply both linear and nonlinear regression models, use feature selection techniques, and implement regularization to improve model accuracy while preventing overfitting.

## Dataset
**Source:** [Kaggle - Cars Dataset](https://www.kaggle.com/datasets/ahmedwaelnasef/cars-dataset/data)  
**Size:** 6,750 rows, 9 columns  
**Target Variable:** Car Price  
**Key Features:** Make, Model, Year, Mileage, Engine Size, and more  
**Preprocessing Requirements:**
- Handle missing values
- Encode categorical features
- Normalize/standardize numerical features
- Convert all prices to a common currency (e.g., USD)
- Split dataset into Training (60%), Validation (20%), and Test (20%) sets

## Project Steps
### 1. Data Preprocessing
- Clean and preprocess the dataset.
- Convert currency to USD.
- Split dataset into train, validation, and test sets.

### 2. Regression Models
Implement the following models:
- **Linear Models:**
  - Ordinary Linear Regression (OLS)
  - LASSO Regression (L1 Regularization)
  - Ridge Regression (L2 Regularization)
  - **Closed-form solution vs. Gradient Descent:** Implement linear regression without external APIs.
- **Nonlinear Models:**
  - Polynomial Regression (degrees 2 to 10)
  - Radial Basis Function (RBF) Regression

### 3. Model Selection Using Validation Set
- Evaluate models using:
  - Mean Squared Error (MSE)
  - Mean Absolute Error (MAE)
  - R-squared (R²)
- Select the best model based on performance on the validation set.

### 4. Feature Selection using Forward Selection
- Start with an empty model and iteratively add features that minimize error.
- Stop when additional features no longer improve performance.

### 5. Regularization Techniques
- Apply **LASSO** and **Ridge** Regression to prevent overfitting.
- Use Grid Search to find the optimal regularization parameter (λ).

### 6. Hyperparameter Tuning
- Use Grid Search to optimize hyperparameters for all models.

### 7. Model Evaluation on Test Set
- Evaluate the best model on the test set to measure generalization.
- Report final performance metrics.

### 8. Optional: Alternative Target Variable
- Identify another relevant target variable and build a regression model.

## Results & Reporting
A detailed report includes:
- Dataset description and preprocessing steps.
- Comparison of regression models and validation performance.
- Feature selection results.
- Regularization results with optimal λ values.
- Best model selection with hyperparameter tuning.
- Final evaluation on the test set.
- Visualizations (feature importance, error distribution, predictions vs. actual values).

## Submission Guidelines
- Submit project files (code + report) as a **ZIP file**.
- Code and report should be in **separate files**.
- Follow naming conventions and submission deadlines.

## Requirements
- Python 3.x
- Libraries: NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn

   
