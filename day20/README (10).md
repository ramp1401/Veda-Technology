# Level 1 - Day 20: Data Types and Type Conversion in Pandas

**Track:** Data Science  
**Task:** Task 20 - Data Types and Type Conversion  
**Tools:** Python 3, Pandas, NumPy, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the official deliverables for **Day 20 (Task 20 - Data Types and Type Conversion)** of the Data Science Internship track. The objective is to inspect, audit, and convert DataFrame columns across diverse data types (`string`, `integer`, `float`, `boolean`, `datetime`, and `category`) to ensure computational efficiency, accurate mathematical aggregation, and data integrity.

---

## 📊 Summary Reference Guide

| Target Data Type | Primary Conversion Method | Role in Data Preprocessing |
| :--- | :--- | :--- |
| **Integer (`int64` / `int32`)** | `df['col'].astype('int32')` | Discrete counts, IDs, age metrics |
| **Float (`float64`)** | `pd.to_numeric(df['col'], errors='coerce')` | Financial values, percentages; safely handles invalid strings |
| **Boolean (`bool`)** | `df['col'].astype(int).astype(bool)` | Flags, indicators, binary logical filtering |
| **Datetime (`datetime64[ns]`)** | `pd.to_datetime(df['col'], format='%Y-%m-%d')` | Time-series, date arithmetic, calendar feature extraction |
| **Category (`category`)** | `df['col'].astype('category')` | Low-cardinality nominal text; drastically reduces RAM overhead |

---

## 📂 Deliverables Included

1. **`Task_20_Data_Types_and_Type_Conversion.ipynb`**:
   - **Initial Data-Type Inspection Report:** Comprehensive breakdown of uncleaned column data types, sample values, and target formats.
   - **Conversions Across 5 Distinct Data Types:**
     1. String to Integer (`StudentID`, `Age`).
     2. String to Boolean (`Fee_Paid`).
     3. Dirty Currency / Invalid String to Float (`Tuition_Fee`, `Exam_Score`) with `errors='coerce'`.
     4. String to Datetime (`Enrollment_Date`) with temporal component extraction (`dt.month_name()`).
     5. String to Categorical (`Department`) with memory profiling.
   - **Memory Usage Profiling:** Demonstrates quantifiable memory savings before and after type optimization.
   - **Cleaned Dataset & Downstream Analytics:** Verification showing correct typing enabling mathematical operations and date math.
2. **`Task_20_Data_Types_and_Type_Conversion.pdf`**:
   - Publication-quality executive PDF formatted directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Ensure Pandas is installed in your workspace:
   ```bash
   pip install pandas numpy jupyter
   ```
2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_20_Data_Types_and_Type_Conversion.ipynb` and select **Kernel > Restart & Run All**.
