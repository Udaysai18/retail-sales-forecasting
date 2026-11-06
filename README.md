# AI-Powered Retail Sales Forecasting System

A data analytics and forecasting project built in a Jupyter notebook. It cleans retail sales data, explores sales patterns, segments stores, forecasts future revenue, and shows the results in an interactive dashboard.

## Dataset
- File: `4877028-Retail_Sales_Data.xlsx`
- 73,000 transactions with date, store, product category, units sold, unit price, discount, revenue, customer type, payment mode, region and holiday flag

## What the notebook does
1. **Data cleaning** - checks data types and missing values, saves `Retail_Sales_Cleaned.csv`
2. **Exploratory analysis** - revenue by product category, store, customer type and time period
3. **Store segmentation** - groups stores with K-Means clustering, saves `store_segmentation_results.csv`
4. **Revenue forecasting** - predicts future monthly revenue using Exponential Smoothing and Linear Regression, saves `future_revenue_forecast.csv`
5. **Interactive dashboard** - Plotly charts with filters for year, store and category, saves `retail_dashboard_data.csv`

## Tech stack
Python 3.13, pandas, NumPy, Matplotlib, Seaborn, Plotly, scikit-learn, statsmodels, ipywidgets

## How to run
1. Clone the repository
2. Create and activate a virtual environment:
