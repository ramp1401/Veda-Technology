# Day 45 — Sales & Service Demand Forecasting System
**Veda Technology | Data Science Internship**

## Overview
A beginner-friendly time-series project that explores historical demand, identifies trend and seasonality, compares baseline/statistical/machine-learning forecasts, evaluates errors, and generates an illustrative 30-day forecast.

## Dataset
`synthetic_service_demand.csv` contains daily synthetic demand from 2023-01-01 through 2025-12-31, plus a simulated promotion flag. It is created for educational purposes and is **not real Veda Technology data**.

## Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn (Random Forest and evaluation metrics)
- statsmodels (Holt-Winters Exponential Smoothing)
- Jupyter Notebook
- Streamlit (optional dashboard)

## Project workflow
1. Load and validate the data.
2. Plot daily demand and rolling averages.
3. Explore weekly and monthly patterns.
4. Split data chronologically into training and final 90-day test windows.
5. Compare naïve, 7-day moving-average, Holt-Winters, and Random Forest models.
6. Evaluate MAE, RMSE, and WAPE.
7. Fit a final Holt-Winters model and forecast the next 30 days.
8. Interpret results for service capacity, staffing, and business planning.

## Setup
```bash
python -m venv .venv
# Windows PowerShell:
.venv\Scripts\Activate.ps1
# macOS/Linux:
# source .venv/bin/activate

pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter streamlit
jupyter notebook
```
Open `Day45_Sales_Service_Demand_Forecasting.ipynb` and run all cells from top to bottom. Keep the CSV in the same folder as the notebook.

## Optional Streamlit dashboard
Copy the Streamlit code from the last notebook section into `app.py`, then run:
```bash
streamlit run app.py
```

## Outputs
The notebook saves:
- `next_30_day_forecast.csv`
- `model_evaluation_results.csv`

## Important limitations
The data is synthetic. Results are illustrative only and must not be represented as actual company forecasts. Forecast accuracy can deteriorate when business conditions change. The Random Forest holdout test uses lag features based on prior observed demand; production multi-step forecasts require a properly designed recursive/direct strategy and ongoing monitoring.
