# Employee Attrition Prediction using PyTorch

## Overview

This project focuses on predicting employee attrition using Deep Learning techniques. Employee attrition is a significant challenge for organizations, leading to increased recruitment costs, productivity loss, and workforce instability. The goal of this project is to identify employees who are likely to leave the company based on various workplace and personal factors.

The project utilizes the IBM HR Analytics Employee Attrition Dataset and implements a complete Machine Learning and Deep Learning pipeline using PyTorch.

---

## Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* One-Hot Encoding of Categorical Features
* Feature Scaling using StandardScaler
* Train-Test Split
* PyTorch Tensor Conversion
* Custom Artificial Neural Network (ANN) Implementation
* Model Training and Validation
* Performance Evaluation
* Correlation Heatmap Visualization
* Employee Attrition Prediction

---

## Dataset

The project uses the IBM HR Analytics Employee Attrition Dataset containing employee-related information such as:

* Age
* Business Travel
* Department
* Education
* Job Role
* Monthly Income
* Overtime
* Work-Life Balance
* Years at Company
* Job Satisfaction

### Target Variable

* Attrition

  * 0 = Employee Stays
  * 1 = Employee Leaves

---

## Technologies Used

* Python
* PyTorch
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn

---

## Neural Network Architecture

Input Layer → 64 Neurons → 32 Neurons → 16 Neurons → Output Layer

### Activation Function

* ReLU

### Loss Function

* BCEWithLogitsLoss

### Optimizer

* Adam Optimizer

---

## Project Workflow

1. Load Dataset
2. Perform Data Preprocessing
3. Handle Categorical Features using One-Hot Encoding
4. Scale Numerical Features
5. Split Data into Training and Testing Sets
6. Convert Data into PyTorch Tensors
7. Create DataLoaders
8. Build ANN Model
9. Train Model
10. Validate Performance
11. Evaluate Results
12. Save Best Model

---

## Visualizations

The project includes:

* Correlation Heatmap
* Feature Analysis
* Training Loss Curves
* Validation Loss Curves
* Confusion Matrix

---

## Results

The Artificial Neural Network successfully learns patterns associated with employee attrition and demonstrates the effectiveness of Deep Learning on structured HR datasets.

Evaluation metrics include:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

---

## Future Improvements

* Hyperparameter Tuning
* Dropout Regularization
* Batch Normalization
* Streamlit Deployment
* SHAP Explainability
* Random Forest & XGBoost Comparison

---

## Repository Structure

```text
├── ANN_PROJECT.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
```

---

## Author

Tushar

This project was developed as part of my Machine Learning and Deep Learning learning journey, with a focus on building practical, industry-relevant solutions using PyTorch.
