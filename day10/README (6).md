# Level 1 - Day 10: Exception Handling in Python (`try-except`)

**Track:** Data Science  
**Task:** Task 10 - Robust Error and Exception Handling for Data Pipelines  
**Tools:** Python 3, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the deliverables for **Task 10 (Data Science Track)**. It focuses on mastering exception handling mechanisms (`try`, `except`, `else`, `finally`, `raise`) to build robust, production-grade data pipelines that handle dirty, corrupted, missing, or irregular records without unexpected crashes.

---

## 📊 Summary Reference Table

| Mechanism / Keyword | Syntax | Data Science Preprocessing Role |
| :--- | :--- | :--- |
| `try` | `try:` | Wraps risky data casting, file reads, or mathematical operations |
| `except` | `except <ErrorType> as err:` | Intercepts runtime errors, isolates faulty rows, triggers imputation |
| `else` | `else:` | Executes strictly when operations in `try` succeed |
| `finally` | `finally:` | Guarantees cleanup (closing DB connections, flushing buffers) |
| `raise` | `raise ValueError(...)` | Enforces data quality gates and triggers custom validation rules |

---

## 📂 Deliverables Included

1. **`Task_10_Exception_Handling_Try_Except.ipynb`**:
   - **8 Core Practical Scenarios:**
     1. Handling `ZeroDivisionError` during KPI metrics calculations.
     2. Handling `ValueError` during dirty string-to-numeric casting.
     3. Handling `TypeError` when dealing with mismatched feature data types.
     4. Handling `KeyError` when parsing irregular dictionary/JSON records.
     5. Handling `IndexError` on missing sequence coordinates.
     6. Multi-exception handling within a single unified `try` block.
     7. Executing the complete `try-except-else-finally` lifecycle.
     8. Raising custom exceptions for data quality assertions.
   - **2 Production-Grade Fault-Tolerant Pipelines:**
     - **Student Exam Ingestion & Grading Engine:** Handles missing keys, corrupt string marks, empty arrays, and logs audit alerts.
     - **Corporate Payroll Parser & Audit Engine:** Sanitizes out-of-bound ratings, negative salaries, and string anomalies.
2. **`Task_10_Exception_Handling_Try_Except.pdf`**:
   - Executive PDF formatted for documentation and submission.

---

## 🚀 How to Run the Notebook

1. Open your terminal in this project repository.
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_10_Exception_Handling_Try_Except.ipynb` and select **Kernel > Restart & Run All**.
