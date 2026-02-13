# walmart_sales_forecasting

## 📊 Project Overview
This project performs time series forecasting on Walmart sales data using Exponential Smoothing.

## 📁 Dataset
Walmart Sales Forecasting Dataset

Columns used:
- Date
- Weekly_Sales

## 🔍 Steps Performed
1. Loaded dataset and converted Date to datetime.
2. Aggregated weekly sales by date.
3. Resampled weekly sales into monthly sales.
4. Plotted sales trend over time.
5. Split data into training and testing sets (80%-20%).
6. Applied Exponential Smoothing model.
7. Forecasted future sales.
8. Evaluated model using MAE and MAPE.
9. Exported forecast results to CSV.

## 📈 Model Performance
- MAE: 2,792,887
- MAPE: 14.27%

The model achieved good forecasting accuracy and successfully captured the overall sales trend.
