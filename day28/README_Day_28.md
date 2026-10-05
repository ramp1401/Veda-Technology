# Day 28 — Decision Tree Classifier

**Veda Technology · Level 2 · Day 28**

## Overview
This project trains a **Decision Tree Classifier** on the Iris dataset and studies how `max_depth` affects model performance and complexity.

## Objective
Understand tree-based classification and model complexity.

## Tools
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Deliverables
- Decision Tree model
- Visualization of the tree
- Performance comparison across tree depths
- Overfitting analysis
- Feature importance

## Workflow
1. Load the Iris dataset.
2. Split data into training and testing sets.
3. Train a Decision Tree.
4. Visualize the tree.
5. Compare depths 1–10.
6. Compare training vs testing accuracy.
7. Analyze overfitting.
8. Inspect feature importance.
9. Generate the final model evaluation.

## Key Concept: `max_depth`
`max_depth` controls the maximum number of levels in the tree.
- Small depth → simpler model and possible underfitting.
- Large depth → more complex model and higher overfitting risk.

## Overfitting
A large difference between training and testing accuracy can indicate overfitting.

`Accuracy Gap = Training Accuracy − Testing Accuracy`

## Interview Questions
**How does a decision tree make predictions?** It follows feature-based rules from the root to a leaf.

**What is overfitting?** When a complex tree learns training-specific noise and performs poorly on unseen data.

**What does `max_depth` control?** The maximum depth and therefore the complexity of the tree.

## Files
- `Day_28_Decision_Tree_Classifier.ipynb`
- `Day_28_Decision_Tree_Classifier.pdf`
- `README_Day_28.md`
