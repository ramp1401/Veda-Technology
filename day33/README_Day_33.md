# Day 33 — Student Performance & Learning Analytics

**Veda Technology · Project 3 of 3**

## Overview
An end-to-end beginner data science project exploring synthetic student academic data: attendance, study habits, subject scores, and final outcomes.

## Objectives
- Clean data and handle missing values and duplicates
- Perform exploratory data analysis (EDA)
- Analyze attendance and subject-wise performance
- Explore numeric correlations
- Engineer features
- Predict final scores using Linear Regression
- Classify pass/fail using Logistic Regression
- Evaluate and interpret model results

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, Git/GitHub.

## Dataset
The notebook creates 300 synthetic student records. It intentionally introduces a few missing values and duplicate rows for cleaning practice. No external dataset is needed.

## Workflow
1. Generate and inspect data
2. Clean duplicates and impute missing numeric values with medians
3. Visualize score distributions and relationships
4. Compare subject averages and attendance bands
5. Examine correlations and engineer features
6. Train/evaluate Linear Regression and Logistic Regression
7. Interpret coefficients and document limitations

## Metrics
- Regression: MAE, RMSE, R²
- Classification: accuracy, precision, recall, F1-score, confusion matrix

## Run the Project
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
jupyter notebook
```
Open `Day_33_Student_Performance_Learning_Analytics.ipynb` and run cells from top to bottom.

## Interview Questions
- What is EDA?
- How do you handle missing values and duplicate rows?
- Correlation vs causation?
- Linear Regression vs Logistic Regression?
- Why use a train/test split?
- What do MAE, RMSE, R², precision, recall, and F1-score mean?
- Why is feature scaling useful?

## Files
- `Day_33_Student_Performance_Learning_Analytics.ipynb`
- `Day_33_Student_Performance_Learning_Analytics.pdf`
- `README_Day_33.md`

## Responsible Use
The dataset is synthetic and results are illustrative. The exploratory review flags are not validated assessments and must not be used for real student decisions.
