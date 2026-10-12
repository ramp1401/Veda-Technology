# Day 35 — Veda Technology Business & Service Analytics

## Overview
An end-to-end Data Science project analyzing synthetic business data for website visitors, internship applications, training programs, IT/digital service inquiries, customers, and marketing channels.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter Notebook. Optional extensions: SQL, Excel, Power BI.

## Files
- `Day_35_Veda_Technology_Business_Service_Analytics.ipynb` — complete notebook.
- `Day_35_Veda_Technology_Business_Service_Analytics.pdf` — PDF export of notebook content.
- `README_Day_35.md` — project documentation.

## Run locally
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
jupyter notebook Day_35_Veda_Technology_Business_Service_Analytics.ipynb
```
Run all cells from top to bottom.

## Workflow
1. Generate synthetic business dataset.
2. Inspect and clean missing values and duplicates.
3. Calculate KPIs.
4. Analyze business areas and monthly trends.
5. Compare marketing channels.
6. Analyze service demand and customer segments.
7. Visualize correlations.
8. Train and evaluate a Random Forest regression model.
9. Write recommendations.

## Privacy and limitations
The dataset is generated in the notebook and does not use confidential Veda Technology data. The `revenue_proxy` is synthetic; charts, model scores, and recommendations are demonstrations, not real company findings or financial forecasts.

## Interview questions
- What is business intelligence, and how does it differ from data analytics?
- Which KPIs measure website and service performance?
- How do you handle missing values and duplicate records?
- Why does correlation not prove causation?
- Why is a train/test split important?
- Explain MAE, RMSE, and R².

**Reproducibility:** random seed `42`.
