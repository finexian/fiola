# FIOLA: Optimizing Credit Risk Decisions Through Trade-Off Analysis — Evidence from Lending Club Data

This repository contains supporting material for evaluating logistic regression models trained on the Fiola framework.

It includes:
1. Two test datasets from the last training epoch.
2. The logistic regression parameters used during model training.
3. The train and test dates for all the epochs

Repository Contents
* X_test36_epoch94.csv – Features for 36-month loan test set (epoch 94)
* y_test36_epoch94.csv – Target variable for 36-month test set (epoch 94)
* X_test60_epoch52.csv – Features for 60-month loan test set (epoch 52)
* y_test60_epoch52.csv – Target variable for 60-month test set (epoch 52)
* logistic_regression_params.json – Best hyperparameters and coefficients used in the trained model.

Usage
These files allow users to validate model performance on the final epoch test sets used in the original Fiola experiments.
You can:
1. Load X_test and y_test to evaluate your own trained model
2. Use the provided logistic regression parameters for benchmarking or replication
