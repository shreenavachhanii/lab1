# Breast Cancer Diagnosis Prediction

This repository contains models for predicting breast cancer diagnosis using the Breast Cancer Wisconsin (Diagnostic) dataset.

## Models

1. **Logistic Regression (`shreenavachhani_model_v1.py`)**
2. **Random Forest (`shreenavachhani_model_v2.py`)**

## Dataset

The dataset is from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic)).

## Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/<yourusername>/<yourrepo>.git
    cd <yourrepo>
    ```

2. Run the Logistic Regression model:
    ```bash
    python shreenavachhani_model_v1.py
    ```

3. Switch to the branch and run the Random Forest model:
    ```bash
    git checkout new_model_branch
    python shreenavachhani_model_v2.py
    ```

## Installation

Install the necessary libraries:
```bash
pip install pandas numpy scikit-learn joblib
