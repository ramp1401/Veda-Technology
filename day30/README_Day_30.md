# Day 30 — K-Nearest Neighbors

**Veda Technology · Level 2 · Day 30 · Data Science Track**

## Overview
Build a **K-Nearest Neighbors (KNN)** classification model and evaluate how different K values affect prediction performance using the Iris dataset.

## Objective
Understand distance-based classification, feature scaling, K selection, and overfitting/underfitting.

## Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Workflow
1. Load and inspect the Iris dataset.
2. Split data into training and testing sets.
3. Scale features with `StandardScaler`.
4. Train KNN.
5. Test K values from 1 to 20.
6. Compare training and testing accuracy.
7. Select the best K.
8. Evaluate with a classification report and confusion matrix.

## Why Scaling Matters
KNN is distance-based. Without scaling, features with larger numerical ranges can dominate distance calculations.

```python
scaler = StandardScaler()
X_train_scaled = scaler.fit_transform(X_train)
X_test_scaled = scaler.transform(X_test)
```

## K Selection
- Small K → more sensitive to noise → possible overfitting.
- Large K → smoother decision boundary → possible underfitting.

## Interview Questions
**How does KNN classify observations?** It finds the K nearest observations and uses majority voting.

**Why is scaling important?** KNN depends on distances between observations.

**What happens when K is too small?** The model may overfit.

**What happens when K is too large?** The model may underfit.

**Is KNN parametric?** KNN is generally considered non-parametric.

## Files
- `Day_30_K_Nearest_Neighbors.ipynb`
- `Day_30_K_Nearest_Neighbors.pdf`
- `README_Day_30.md`

## Run
```bash
pip install numpy pandas scikit-learn matplotlib jupyter
jupyter notebook
```
