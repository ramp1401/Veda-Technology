# Level 1 - Day 9: NumPy Arrays and Vectorized Computing

**Track:** Data Science  
**Task:** Task 9 - Numerical Computing with NumPy Arrays  
**Tools:** Python 3, NumPy, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the deliverables for **Task 9 (Data Science Track)**. It focuses on mastering NumPy N-dimensional arrays (`ndarray`), multidimensional indexing, array slicing, broadcasting arithmetic, axis-based statistical aggregations, and feature scaling pipelines commonly applied in machine learning preprocessing.

---

## 📊 Summary Reference Table

| Feature / Operation | NumPy Syntax | Primary Data Science Application |
| :--- | :--- | :--- |
| **Array Creation** | `np.zeros()`, `np.ones()`, `np.arange()`, `np.linspace()` | Weight initialization, grid searches, step generations |
| **Attribute Inspection** | `.ndim`, `.shape`, `.size`, `.dtype` | Matrix compatibility audits, tensor debugging |
| **Multi-axis Slicing** | `arr[start:stop:step, col_start:col_stop]` | Feature extraction, batch window slicing, submatrix isolation |
| **Boolean Masking** | `arr[arr > threshold]` | Noise filtering, outlier isolation, conditional segmenting |
| **Broadcasting** | `matrix + bias_vector` | Bias addition, scale factor normalization |
| **Axis Aggregation** | `np.mean(axis=0)`, `np.std(axis=1)` | Feature-wise metrics (columns) and row-wise instance stats |
| **Conditional Transform** | `np.where(condition, x, y)` | Vectorized binary labeling, curved adjustments |

---

## 📂 Deliverables Included

1. **`Task_9_NumPy_Arrays_and_Vectorized_Computing.ipynb`**:
   - **8 Core Array Scenarios:**
     1. Array initialization variants (`zeros`, `ones`, `arange`, `linspace`).
     2. Comprehensive attribute inspection (`ndim`, `shape`, `size`, `dtype`, `itemsize`).
     3. 2D grid multi-axis slicing and column extraction.
     4. Boolean masking and threshold outlier isolation.
     5. Vectorized arithmetic and row-wise broadcasting.
     6. Axis-based statistical aggregations across columns (`axis=0`) and rows (`axis=1`).
     7. Matrix reshaping, transposition (`.T`), and flattening (`.ravel()`).
     8. Vectorized conditional replacements using `np.where()`.
   - **2 Applied Machine Learning Preprocessing Pipelines:**
     - **Feature Scaling Pipeline:** Computes vectorized Min-Max Normalization and Z-Score Standardization across multi-column student features.
     - **Employee Payroll & Appraisal Analytics Engine:** Computes vectorized appraisal hikes, revised payouts, and overall payroll impact statistics.
2. **`Task_9_NumPy_Arrays_and_Vectorized_Computing.pdf`**:
   - Professional, submission-ready PDF generated directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Ensure NumPy and Jupyter are installed:
   ```bash
   pip install numpy jupyter
   ```
2. Launch Jupyter Notebook in this workspace:
   ```bash
   jupyter notebook
   ```
3. Open `Task_9_NumPy_Arrays_and_Vectorized_Computing.ipynb` and run all cells via **Kernel > Restart & Run All**.
