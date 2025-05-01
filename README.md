# Fiola

## Test Data & Logistic Regression Parameters
This repository contains supporting material for evaluating logistic regression models trained on the Fiola framework.

It includes:
1. Two test datasets from the last training epoch.
2. The logistic regression parameters used during model training.

Repository Contents
X_test36.csv – Features for 36-month loan test set
y_test36.csv – Target variable for 36-month test set
X_test60.csv – Features for 60-month loan test set
y_test60.csv – Target variable for 60-month test set
logistic_regression_params.json – Best hyperparameters and coefficients used in the trained model.

Usage
These files allow users to validate model performance on the final epoch test sets used in the original Fiola experiments.
You can:
1. Load X_test and y_test to evaluate your own trained model
2. Use the provided logistic regression parameters for benchmarking or replication
