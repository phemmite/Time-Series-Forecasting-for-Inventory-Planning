# 📈 Time Series Forecasting for Inventory Planning

## 📌 Project Overview
The inventory management team needs to determine how many units of a key product to stock for the next quarter.  
This project builds a **time-series forecasting model using Facebook Prophet** to support data-driven inventory decisions.

---

## 🎯 Objectives
- Identify trends and seasonality in historical sales
- Forecast future demand
- Evaluate model accuracy using RMSE and MAPE
- Provide clear business recommendations

---

## 📊 Dataset
- Superstore Sales Dataset (Kaggle)
- Monthly aggregated sales

---

## 🧠 Methodology
1. Data cleaning and aggregation
2. Exploratory time series analysis
3. Train-test split (80/20)
4. Forecasting using **Prophet**
5. Model evaluation (RMSE, MAPE)
6. Visualization and business interpretation

---

## 🔮 Forecasting Model
- Model: Facebook Prophet
- Seasonality: Yearly
- Forecast Horizon: Next quarter (3 months)

---

## 📈 Results
- **MAPE:** ~12%
- **Trend:** Steady upward growth
- **Seasonality:** Strong year-end sales peaks

---

## ✅ Business Recommendation
Sales are projected to **increase by approximately 15% next quarter**.  
The inventory team should **increase stock levels by 15–20%** to meet demand and prevent stock-outs.

---

## 📊 Dashboard
A Power BI dashboard visualizes:
- Actual vs Forecasted Sales
- Expected Growth
- Forecasted Demand

---

## 🛠 Tools Used
- Python
- Pandas
- Prophet
- Matplotlib
- Power BI

---

## 📌 How to Run
```bash
pip install -r requirements.txt

---bash (notebooks/sales_forecasting_prophet.ipynb)



