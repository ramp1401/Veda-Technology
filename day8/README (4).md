# Level 1 - Day 8: Iteration and Loops in Python (`for` & `while`)

**Track:** Data Science  
**Task:** Task 8 - Iteration and Control Flow for Batch Data Processing  
**Tools:** Python 3, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the deliverables for **Task 8 (Data Science Track)**. It focuses on using Python loops (`for`, `while`) alongside flow control keywords (`break`, `continue`, `else`) and iterator utilities (`enumerate()`, `zip()`, `range()`) for batch record processing, data cleaning, and aggregation.

---

## 📊 Summary Reference Table

| Mechanism | Syntax | Data Science Use Case |
| :--- | :--- | :--- |
| `for ... in` | `for item in sequence:` | Record-by-record dataset traversal and feature calculation |
| `while` | `while condition:` | Convergence checks, optimization epochs, and simulation steps |
| `enumerate()` | `for idx, val in enumerate(seq):` | Line-by-line file parsing and index-based flagging |
| `zip()` | `for x, y in zip(seq1, seq2):` | Simultaneous evaluation (e.g., ground truth vs predictions) |
| `break` / `continue` | `break` / `continue` | Early stopping on anomaly detection, bypassing corrupt values |

---

## 📂 Deliverables Included

1. **`Task_8_Iteration_and_Loops.ipynb`**:
   - **8 Targeted Loop Examples:**
     1. Standard `for` loop accumulation (manual mean and sum computation).
     2. Index tracking using `enumerate()` for threshold inventory alerts.
     3. Multi-sequence traversal using `zip()` to compute prediction residuals.
     4. `while` loop implementation of convergence/loss tolerance simulation.
     5. Data sanitization using `continue` to filter corrupt and null values.
     6. Anomaly-triggered early stopping with `break`.
     7. 2D nested matrix normalization using inner and outer `for` loops.
     8. Target search loop using Python's loop `else` fallback clause.
   - **2 Applied Data Pipelines:**
     - **Batch Student Performance Evaluator:** Nested loop calculating individual averages and overall cohort statistics.
     - **Departmental Spend & Appraisal Engine:** Iterative evaluation updating compensation tiers and aggregating department budgets.
2. **`Task_8_Iteration_and_Loops.pdf`**:
   - Polished, ready-to-submit PDF generated directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Open your terminal in this repository folder.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_8_Iteration_and_Loops.ipynb` and execute all cells via **Kernel > Restart & Run All**.
