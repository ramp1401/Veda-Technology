# Day 25 — Logistic Regression Classification

**Veda Technology · Data Science Track · Level 2 · Day 25**

## Overview
Build and evaluate a Logistic Regression model for binary classification using the Breast Cancer Wisconsin Dataset from scikit-learn.

## Objective
Understand Logistic Regression as an important baseline classification algorithm and evaluate predictions on unseen data.

## Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Dataset
Breast Cancer Wisconsin Dataset. The target classes are `0 = malignant` and `1 = benign`.

## Workflow
1. Load and inspect data
2. Check missing values
3. Split into training and testing sets
4. Standardize features
5. Train Logistic Regression
6. Generate predictions
7. Use `predict_proba()` for class probabilities
8. Evaluate accuracy and classification report
9. Inspect the confusion matrix
10. Interpret the model

## Key Concepts
### Logistic Regression
A supervised classification algorithm that estimates class probabilities and converts them into class predictions using a decision threshold.

### Feature Scaling
`StandardScaler` is fitted on training data and then used to transform test data, preventing test-set information from leaking into training.

### `predict_proba()`
Returns estimated probabilities for each class for every sample.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

## How to Run
```bash
pip install numpy pandas scikit-learn jupyter
jupyter notebook
```
Then open `Day_25_Logistic_Regression_Classification.ipynb` and run all cells.

## Files
```text
Day_25_Logistic_Regression_Classification.ipynb
Day_25_Logistic_Regression_Classification.pdf
README_Day_25.md
```

## Interview Questions
- What is Logistic Regression?
- Why is Logistic Regression used for classification?
- What does `predict_proba()` return?
- Why should numerical features be scaled?
- What is data leakage?

## Conclusion
This project demonstrates an end-to-end binary classification workflow from preprocessing to model evaluation.
