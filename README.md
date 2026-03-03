# 📊 Sales Demand Forecasting — FUTURE_ML_01

## 🔍 Objective
Build a sales forecasting system that helps businesses predict future demand using historical sales data.

This model is useful for:
- Inventory planning
- Staffing optimization
- Cash flow forecasting
- Strategic decision making

---

## 🧠 Dataset
We used the **Store Sales — Time Series Forecasting** dataset from Kaggle:

📦 https://www.kaggle.com/competitions/store-sales-time-series-forecasting

This dataset contains historical daily sales from multiple stores and product families.

---

## 🚀 Project Workflow

### 1. Data Loading & Cleaning  
- Loaded historical sales data
- Handled missing values and checked data quality

### 2. Feature Engineering  
Created time-based and lag features:
- Month, day, day of week
- Lag sales (previous day)
- Rolling averages (7-day)

These help capture trend and seasonality.

### 3. Train/Test Split  
We used a proper time-based split (no random shuffle) to prevent data leakage.

### 4. Model Training  
Built a baseline model and evaluated with:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)

---

## 📈 Results

| Metric | Score |
|--------|-------|
| MAE    | _Your value here_ |
| RMSE   | _Your value here_ |

Visualization:
- Actual vs Predicted sales plot
- Seasonal trend plots (monthly, weekly)

---

## 📊 Business Interpretation

This forecast helps non-technical stakeholders:

✔ Plan inventory ahead of seasonal peaks  
✔ Optimize staffing during low demand  
✔ Prepare cash flow projections  
✔ Reduce waste and overstock costs

---

## 📁 Files in this Repository

| File | Description |
|------|-------------|
| `Sales_Demand_Forecasting_FUTURE_ML_01.ipynb` | Main Colab Notebook |
| `README.md` | This project overview |
| `/screenshots/` | Optional visual examples |

---

## 📌 How to Run

1. Open in Google Colab
2. Upload dataset files
3. Run all cells
4. Inspect output and plots

---

## 🔗 Notebook
[Sales_Demand_Forecasting_FUTURE_ML_01.ipynb](./Sales_Demand_Forecasting_FUTURE_ML_01.ipynb)
