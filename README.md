# Customer Churn Prediction Using Deep Learning

**ITC 3154 – Cognitive Computing**  
Deree – The American College of Greece  
Fall Semester 2026

## Project Overview

The purpose of this project is to predict customer churn using two different neural network architectures: a Standard Multilayer Perceptron (MLP) and a Residual MLP.

The project focuses on data exploration, preprocessing, model training, hyperparameter tuning and comparison of the two models.

## Dataset

The dataset used is the Telco Customer Churn dataset from Kaggle.

https://www.kaggle.com/datasets/blastchar/telco-customer-churn

- 7,043 customer records
- 21 original columns
- 19 input features before encoding
- 45 input features after preprocessing
- Binary target variable: Churn (0 = Stayed, 1 = Left)

## Team Members and Responsibilities

| Member | Responsibilities |
|---|---|
| Christos Zotos | Data exploration, cleaning, feature selection, preprocessing, dataset splitting and Standard MLP architecture |
| Manthos Balouris | Standard MLP training, hyperparameter tuning and final model comparison |
| Petros Ventikos | Residual MLP architecture, training and hyperparameter tuning |

## Data Preparation

The following steps have been completed:

- Exploratory data analysis and visualizations
- Missing value investigation and handling
- Duplicate record checks
- Correlation analysis
- Removal of customer identifiers
- Binary target encoding
- Stratified dataset splitting
- One-hot encoding
- Numerical feature standardization
- Exporting the prepared datasets

## Prepared Datasets

| File | Records | Purpose |
|---|---:|---|
| churn_train.csv | 4,930 | Model training |
| churn_validation.csv | 1,056 | Validation and hyperparameter tuning |
| churn_test.csv | 1,057 | Final model evaluation |

Each prepared dataset contains 45 input features and one target column.

Both models must use the same prepared datasets to ensure a fair comparison.

## Standard MLP Architecture

- Input layer: 45 features
- First hidden layer: 64 neurons with ReLU
- Second hidden layer: 32 neurons with ReLU
- Output layer: 1 logit
- Trainable parameters: 5,057

The architecture has been constructed and tested successfully. Model training and optimization are the next steps.

## Technologies and Libraries

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch
- GitHub

## Execution Instructions

1. Download the original Telco Customer Churn dataset from Kaggle.
2. Open Christos_Data_Preparation.ipynb in Google Colab.
3. Upload the original CSV and execute all cells in order.
4. Generate the three prepared CSV files.
5. Open Standard_MLP_Architecture.ipynb to examine the Standard MLP structure.
6. Continue with the model training notebooks once available.

## GitHub Collaboration

Each team member works on a separate branch:

- christos-data
- manthos-mlp
- petros-residual

Completed changes are merged into the main branch through pull requests.

## Academic Purpose

This project is being developed for the ITC 3154 Cognitive Computing course for educational purposes.
