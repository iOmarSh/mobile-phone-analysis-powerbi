# 📱 Mobile Phones Analysis – Power BI Dashboard

An end-to-end data analysis project using **Python (Pandas)** and **Power BI** to explore and compare mobile phone specifications and prices across different countries.

## 🚀 Project Overview
This project focuses on:
- Cleaning and structuring messy mobile phone data
- Handling mixed units (GB / TB, mAh, inches, currencies)
- Building interactive Power BI dashboards for comparison and insights

## 🧹 Data Cleaning
Data cleaning was done using **Pandas** in a Jupyter Notebook:
- Extracted numeric values from text using regex
- Normalized storage, RAM, battery, and screen size
- Handled unavailable prices and missing values
- Prepared country-wise prices for Power BI analysis

Notebook: `notebook/data_cleaning.ipynb`

## 📊 Power BI Dashboard
The Power BI report contains **one page**:

### Page 1 – Market Overview
- Number of models per launch year  
- Top 5 most expensive models  
- Average price by brand over years  
- Market share of top brands
- Full comparison table with all specifications
- Dynamic filtering by brand, RAM, storage, year, and price
- Country-based price selection  


## 🛠 Tools & Technologies
- Python (Pandas, Regex)
- Jupyter Notebook
- Power BI
- Git & GitHub

## 📁 Dataset
Cleaned dataset available in: https://www.kaggle.com/code/iomars/mobile-analysis-ready-for-powerbi
