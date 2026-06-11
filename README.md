# breast-cancer-prediction-ml

# Breast Cancer Prediction Using Machine Learning

## Project Overview

This project uses Machine Learning techniques to predict whether a breast tumor is Malignant (Cancerous) or Benign (Non-Cancerous) based on medical diagnostic measurements.

The model is trained using the Breast Cancer Wisconsin Dataset and includes data analysis, visualization, model training, evaluation, and risk assessment.

---

## Objectives

- Analyze breast cancer diagnostic data
- Visualize important patterns and correlations
- Build a machine learning classification model
- Predict whether a tumor is malignant or benign
- Generate risk assessments based on prediction probabilities

---

## Dataset

The project uses the Breast Cancer Wisconsin Dataset available in Scikit-Learn.

### Dataset Information

- Total Samples: 569
- Features: 30
- Classes:
  - Malignant (Cancerous)
  - Benign (Non-Cancerous)

Features include:

- Mean Radius
- Mean Texture
- Mean Perimeter
- Mean Area
- Mean Smoothness
- Mean Compactness
- Mean Concavity
- Mean Symmetry
- And several other diagnostic measurements

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

- Load Breast Cancer dataset from Scikit-Learn
- Convert data into a Pandas DataFrame

### 2. Exploratory Data Analysis

- Dataset overview
- Statistical summaries
- Class distribution analysis

### 3. Data Visualization

- Cancer distribution plot
- Correlation heatmap
- Feature comparison boxplots

### 4. Model Building

- Train-Test Split
- Logistic Regression Classifier

### 5. Model Evaluation

- Accuracy Score
- Confusion Matrix
- Classification Report

### 6. Risk Assessment

A custom function categorizes predictions into:

| Probability | Risk Level |
|------------|------------|
| < 30% | Low Risk |
| 30% - 70% | Medium Risk |
| > 70% | High Risk |

---

## Machine Learning Model

Algorithm Used:

- Logistic Regression

Why Logistic Regression?

- Simple and interpretable
- Effective for binary classification problems
- Provides probability estimates for risk assessment

---

## Results

The model achieves high classification accuracy on the test dataset and successfully predicts whether a tumor is malignant or benign.

Evaluation metrics include:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## Visualizations Included

### Cancer Distribution

Shows the distribution of benign and malignant cases.

### Correlation Heatmap

Displays relationships between medical features.

### Feature Analysis

Comparison of important features across cancer classes.

---

