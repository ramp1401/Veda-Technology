# Day 27 — Confusion Matrix and Threshold Tuning

**Veda Technology · Data Science Track · Level 2 · Day 27**

## Overview
This project analyzes classification predictions using a confusion matrix and investigates how probability thresholds affect precision, recall, accuracy and F1-score.

## Objective
Understand the relationship between probability thresholds and classification performance.

## Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset
**Breast Cancer Wisconsin Dataset** from scikit-learn. Target: `0 = malignant`, `1 = benign`.

## Workflow
1. Load and inspect the dataset
2. Split and scale data
3. Train Logistic Regression
4. Get probabilities with `predict_proba()`
5. Evaluate threshold 0.50
6. Visualize confusion matrix
7. Test thresholds 0.20–0.80
8. Compare precision, recall, accuracy and F1
9. Select the tested threshold with the highest F1-score
10. Discuss false-positive/false-negative costs

## Key Concepts
A confusion matrix contains TP, TN, FP and FN. Lowering a classification threshold generally increases recall but may reduce precision. Raising it generally does the opposite. The best threshold depends on the application's error costs.

## Run
```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
jupyter notebook
```
Open `Day_27_Confusion_Matrix_and_Threshold_Tuning.ipynb` and run all cells.

## Interview Questions
- What is a confusion matrix?
- How does changing the threshold affect recall?
- Why might the default 0.5 threshold not be optimal?

## Files
```text
Day_27_Confusion_Matrix_and_Threshold_Tuning.ipynb
Day_27_Confusion_Matrix_and_Threshold_Tuning.pdf
README_Day_27.md
```

---
**Day 27 — Confusion Matrix and Threshold Tuning 📊**
