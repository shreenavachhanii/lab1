# Breast Cancer Diagnosis Prediction

This repository contains Python scripts to build and evaluate machine learning models for predicting breast cancer diagnosis using the Breast Cancer Wisconsin (Diagnostic) dataset.

## Summary of the Code

### `shreenavachhani_model_v1.py`

- **Imports necessary libraries**: pandas, numpy, scikit-learn, joblib.
- **Loads the dataset**: Reads data from the UCI Machine Learning Repository.
- **Preprocesses the data**:
  - Drops the ID column.
  - Encodes the target variable (Diagnosis) as 0 (Benign) and 1 (Malignant).
  - Splits the data into training and testing sets.
  - Scales the feature values.
- **Trains a Logistic Regression model** on the training data.
- **Evaluates the model**:
  - Makes predictions on the test data.
  - Computes accuracy, confusion matrix, and classification report.
- **Saves the trained model** using joblib.

### `shreenavachhani_model_v2.py` (on a separate branch)

- Similar data preprocessing steps as the logistic regression script.
- **Trains a Random Forest model** on the training data.
- **Evaluates the model** with accuracy, confusion matrix, and classification report.
- **Saves the trained model** using joblib.

These scripts are designed to predict whether a breast cancer tumor is malignant or benign based on 30 features derived from digitized images of fine needle aspirate (FNA) of breast masses.
