# Level 1 - Day 18: Missing Values in Pandas

**Track:** Data Science  
**Task:** Task 18 - Missing Values in Pandas  
**Tools:** Python 3, Pandas, NumPy, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the deliverables for **Task 18 (Data Science Track)**. The objective is to identify, summarize, and handle missing values in tabular datasets using modern Pandas workflows (`isna()`, `notna()`, `fillna()`, `dropna()`) and evaluate the trade-offs of dropping versus disciplined statistical imputation.

---

## 📊 Summary Reference Guide

| Function / Technique | Syntax Example | Role in Data Cleaning |
| :--- | :--- | :--- |
| `isna()` / `isnull()` | `df.isna()` | Identifies null/missing values element-wise |
| `notna()` / `notnull()` | `df.notna()` | Filters complete, non-null records |
| `isna().sum()` | `df.isna().sum()` | Computes missing value counts per feature column |
| Missing Percentage | `(df.isna().mean() * 100)` | Assesses missingness proportion to guide strategy |
| Row Dropping | `df.dropna(subset=['id'])` | Removes unrecoverable rows lacking critical keys |
| Mean Imputation | `df['col'].fillna(mean_val)` | Imputes normally distributed numerical data |
| Median Imputation | `df['col'].fillna(median_val)` | Imputes skewed numerical data with outliers |
| Mode Imputation | `df['col'].fillna(mode_val)` | Imputes categorical features with majority class |

---

## 📂 Deliverables Included

1. **`Task_18_Missing_Values_in_Pandas.ipynb`**:
   - **Missing-Value Audit Summary:** Column-wise breakdown of null counts and percentages.
   - **Detection & Filtering:** Code examples utilizing `isna()` and `notna()` for subset isolation.
   - **Comparison of Strategies:** Practical demonstration showing why naive row deletion (`dropna()`) leads to severe data loss.
   - **Disciplined Imputation:** Statistical imputation using column-appropriate median, mean, and mode values.
   - **Cleaned Dataset & Downstream Feature Engineering:** Final verification proving 0 remaining nulls and calculating composite outcome metrics.
2. **`Task_18_Missing_Values_in_Pandas.pdf`**:
   - Executive PDF publication generated directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Ensure Pandas is installed in your Python environment:
   ```bash
   pip install pandas numpy jupyter
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_18_Missing_Values_in_Pandas.ipynb` and select **Kernel > Restart & Run All**.
