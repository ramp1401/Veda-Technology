# Level 1 - Day 7: Conditional Logic & Decision Making (`if-else`)

**Track:** Data Science  
**Task:** Task 7 - Advanced Conditional Logic for Data Preprocessing and Validation  
**Tools:** Python 3, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the complete deliverables for **Task 7 (Data Science Track)**. It focuses on using structured conditional statements (`if`, `elif`, `else`, ternary operators, and compound boolean logic) to solve real-world data validation, anomaly handling, missing feature auditing, and multi-tier categorization challenges.

---

## 📊 Summary Reference Table

| Structure / Keyword | Syntax | Primary Data Science Application |
| :--- | :--- | :--- |
| `if` | `if condition:` | Single-criterion filtering, mandatory schema assertions |
| `elif` | `elif condition:` | Continuous variable binning (e.g., LTV tiers, age cohorts) |
| `else` | `else:` | Default fallbacks, out-of-bounds anomaly handling |
| Ternary Operator | `x = a if cond else b` | Inline feature engineering and binary target creation |
| Logical Operators | `and`, `or`, `not` | Strict/flexible filtering, missing attribute detection |

---

## 📂 Deliverables Included

1. **`Task_7_Conditional_Statements_If_Else.ipynb`**:
   - **8 Distinct Conditional Scenarios:**
     1. Threshold comparisons for model deployment metrics.
     2. Multi-tier numerical binning (`elif`) for customer lifetime value (LTV).
     3. Dual-criteria validation with `and` (credit limit policies).
     4. High-risk flag detection with `or` (fraud prevention triggers).
     5. Input data completeness auditing with `not` and string sanitation.
     6. Hierarchical decision making via nested `if-else` blocks (scholarship allocation).
     7. Range bounding checks using chained comparisons (`10 <= temp <= 40`).
     8. Ternary inline expressions combined with membership testing (`in`).
   - **2 End-to-End Production Pipelines:**
     - **Academic Cohort Evaluation & Remediation Pipeline:** Evaluates scores, attendance, and assignment completion flags to recommend tailored action plans.
     - **Enterprise Compensation & Appraisal Engine:** Computes dynamic appraisal hikes, bonus allocations, and updated payroll salaries.
2. **`Task_7_Conditional_Statements_If_Else.pdf`**:
   - Executive-grade, publication-ready PDF generated directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Open your terminal in this project directory.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_7_Conditional_Statements_If_Else.ipynb` and run all cells via **Kernel > Restart & Run All**.
