# Level 1 - Day 19: Handling Null Values & Advanced Imputation in Pandas

**Track:** Data Science  
**Task:** Task 19 - Advanced Null Value Profiling, Imputation Strategies, and Data Cleaning  
**Tools:** Python 3, Pandas, NumPy, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the deliverables for **Task 19 (Data Science Track)**. It covers advanced null value profiling and imputation workflows in Pandas, moving beyond simple scalar replacements into group-wise transformations, sequential interpolation, and feature-level missingness indicators.

---

## 📊 Summary Reference Guide

| Strategy / Technique | Pandas Syntax | Best Applied In Data Science |
| :--- | :--- | :--- |
| **Sentinel Replacement** | `df.replace(-999, np.nan)` | Standardizing hidden missing sentinels to `NaN` |
| **Null Profiling** | `df.isnull().sum()`, `df.isnull().mean()` | Diagnosing completeness ratios across dataset columns |
| **Linear Interpolation** | `df['col'].interpolate(method='linear')` | Time-series, financial stock curves, continuous telemetry |
| **Group-wise Imputation** | `df.groupby('dept')['sal'].transform('median')` | Segment-conditioned filling (e.g., salaries per title/dept) |
| **Missingness Indicator** | `df['col'].isnull().astype(int)` | Preserving missing value signal as a predictive feature |
| **Sequential Fill** | `df['col'].ffill().bfill()` | Cascading status and last-known sensor states |

---

## 📂 Deliverables Included

1. **`Task_19_Null_Values_in_Pandas.ipynb`**:
   - Sentinel placeholder (-999) replacement to true `np.nan`.
   - Comprehensive null percentage audit summary.
   - Linear interpolation on continuous time-series metrics.
   - Group-wise conditional imputation based on departmental medians.
   - Binary missingness indicator column generation.
   - Verification confirming zero remaining null values.
2. **`Task_19_Null_Values_in_Pandas.pdf`**:
   - Publication-quality executive PDF formatted directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Ensure Pandas is installed:
   ```bash
   pip install pandas numpy jupyter
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_19_Null_Values_in_Pandas.ipynb` and select **Kernel > Restart & Run All**.
