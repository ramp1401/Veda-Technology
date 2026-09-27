# Level 1 - Day 16: Encapsulation and Data Protection in Python

**Track:** Data Science  
**Task:** Task 16 - Encapsulation and Information Hiding  
**Tools:** Python 3, Jupyter Notebook  

---

## 📌 Project Overview
This repository contains the official deliverables for **Day 16 (Task 16 - Encapsulation and Information Hiding)** of the Data Science Internship track.

### 🎯 Objective
Master public, protected (_var), and private (__var) access modifiers, getter/setter patterns, the @property decorator, and protecting sensitive machine learning states.

---

## 📊 Summary Reference Guide

| Access Modifier | Naming Convention | Intended Usage |
| :--- | :--- | :--- |
| Public | self.name | Freely accessible from anywhere |
| Protected | self._model_type | Internal module/subclass convention (hint) |
| Private | self.__api_key | Name mangling to prevent outside modification |
| @property Getter | @property def balance(self): | Clean read-only access to managed attributes |
| @setter Decorator | @balance.setter def balance(self, val): | Input validation and quality constraint checks |

---

## 📂 Deliverables Included

1. **`Task_16_Encapsulation.ipynb`**:
   - Comprehensive reference notes and concept breakdowns.
   - Practical standalone code demonstrations covering every core syntax and operator.
   - Full applied data pipeline executing realistic data science workloads.
2. **`Task_16_Encapsulation.pdf`**:
   - Publication-quality executive PDF formatted directly from the notebook.

---

## 🚀 How to Run the Notebook

1. Open your terminal in this repository.
2. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
3. Open `Task_16_Encapsulation.ipynb` and select **Kernel > Restart & Run All**.
