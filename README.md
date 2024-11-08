---

# Logistic Regression Model

## Overview
This project demonstrates the implementation of a **Logistic Regression** model using Python and the `scikit-learn` library.
The goal is to classify whether a tumor is malignant or benign using the **Breast Cancer dataset** available in `scikit-learn`.

## Methodology

### Data Collection
- The dataset used in this project is the **Breast Cancer dataset** from the `scikit-learn` library.
- The dataset includes:
  - **Features (`x`)**: Various measurements related to the tumor cells.
  - **Target (`y`)**: Binary classification where `1` indicates a malignant tumor and `0` indicates a benign tumor.

### Data Preprocessing
- The dataset is split into **75% training data** and **25% test data** using the `train_test_split` function from `scikit-learn`.

### Model Training
- A **Logistic Regression** model is instantiated using `scikit-learn`.
- The model is trained on the training data to classify tumors based on the features.

### Prediction
- The trained model is used to make predictions on the test dataset.
- The model’s predictions are compared against the actual labels.

### Evaluation
- The performance of the model is evaluated using:
  - **Confusion Matrix**: Shows the counts of True Positives, False Positives, True Negatives, and False Negatives.
  - **Accuracy Score**: Measures the percentage of correctly classified instances.

## Requirements
```bash
pip install scikit-learn
```

## Results
This project produces the following outputs:
- **Confusion Matrix**: Displays the number of correct and incorrect predictions.
- **Accuracy Score**: Indicates the model's prediction accuracy as a percentage.
- 
---
