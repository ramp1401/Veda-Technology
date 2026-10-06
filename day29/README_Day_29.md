# Day 29 — Random Forest Classifier

**Veda Technology · Level 2 · Day 29 · Data Science Track**

## Overview
Build a **Random Forest classification model** and compare it with a single **Decision Tree** using the Breast Cancer Wisconsin Dataset.

## Objective
Understand ensemble learning and why combining multiple trees can improve generalization.

## Tools
- Python
- Pandas
- Scikit-learn
- Jupyter Notebook
- Matplotlib

## Deliverables
- Random Forest model
- Decision Tree baseline
- Performance comparison
- `n_estimators` experiment
- Feature importance analysis
- Classification report and confusion matrix

## Workflow
1. Load and inspect the dataset.
2. Split into training and testing data.
3. Train a Decision Tree baseline.
4. Train a Random Forest.
5. Compare training and testing accuracy.
6. Test `n_estimators` values: 10, 25, 50, 100, 200, 300.
7. Analyze feature importance.
8. Evaluate generalization and the training-testing gap.

## Key Concepts

### Random Forest
Random Forest is an ensemble method that combines many decision trees to produce a more robust model.

### `n_estimators`
Controls the number of trees in the forest.

### `feature_importances_`
Provides an estimate of the contribution of each feature to impurity reduction.

### Overfitting
A model may overfit when it performs much better on training data than on unseen test data.

`Accuracy Gap = Training Accuracy − Testing Accuracy`

## Interview Questions
1. **What is a Random Forest?** An ensemble of decision trees.
2. **Why can it generalize better than one tree?** Combining many trees generally reduces variance.
3. **What is ensemble learning?** Combining multiple models to improve predictions.
4. **What does `n_estimators` control?** The number of trees.
5. **What is `feature_importances_`?** A measure of feature contribution to impurity reduction.

## Files
- `Day_29_Random_Forest_Classifier.ipynb`
- `Day_29_Random_Forest_Classifier.pdf`
- `README_Day_29.md`

## Run
```bash
pip install pandas scikit-learn matplotlib jupyter
jupyter notebook
```

Open the notebook and run all cells from top to bottom.
