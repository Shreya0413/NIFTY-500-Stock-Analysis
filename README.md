# 📊 NIFTY 500 Stock Analysis – Exploratory Data Analysis Project

## 🚀 Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the NIFTY 500 stocks dataset to extract meaningful insights from the Indian equity market.  

It showcases skills in **data cleaning**, **feature engineering**, and **visualization** using Python libraries like Pandas, Matplotlib, and Seaborn.  

The analysis uncovers patterns in stock prices, trading volumes, volatility, and sector performance, making it highly relevant for financial analysts, data scientists, and portfolio managers.  

---

## 🎯 Objective
- 🧹 Clean and preprocess stock market data for analysis  
- ⚡ Engineer features to enhance insights (e.g., volatility, price range)  
- 📊 Perform EDA to identify trends in the Indian stock market  
- 📈 Visualize key metrics like market value, price changes, and trading activity  
- 📌 Provide actionable insights to support investment decisions  

---

## 📂 About the Dataset
- **Source:** [Kaggle – NIFTY500 Stocks Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/nifty500-stocks-dataset)
- **Format:** CSV
- **Rows:** ~500 companies
- **Columns:**
  - 🏢 Company Information: `Company Name`, `Symbol`, `Industry`
  - 📈 Stock Prices: `Open`, `High`, `Low`, `Previous Close`, `Last Traded Price`
  - 🔥 Price Movements: `Change`, `Percentage Change`, `30 Day % Change`, `365 Day % Change`
  - 📊 Trading Activity: `Share Volume`, `Value (Indian Rupee)`
  - 📆 52-Week Range: `52 Week High`, `52 Week Low`

---

## 🛠 Technologies Used
- 🐍 **Python**
- 📦 Libraries:
  - Pandas
  - Matplotlib
  - Seaborn
- 📓 Jupyter Notebook

---

## 📊 Features of the Project
### 🧹 Data Preprocessing
- Cleaned and standardized column names
- Converted numerical columns for calculations
- Handled missing data by dropping critical rows

### ⚡ Feature Engineering
- **Price Range** = High - Low
- **Price Range %** = (Price Range / Open) × 100
- **Average Price** = Mean of Open, High, Low, Last Traded Price
- **Volatility Proxy** = Price Range %
- **Ranking** = Stocks ranked by 30 Day % Change

### 📈 Exploratory Data Analysis (10 Visualizations)
1. Top 10 Companies by Market Value
2. Distribution of Daily Percentage Change
3. Industry-wise Average Last Traded Price
4. Boxplot of 52 Week High Prices by Industry
5. Correlation Heatmap of Numeric Features
6. Top 10 Most Volatile Stocks
7. Share Volume vs. Last Traded Price (Log Scale)
8. 30 Day vs. 365 Day % Change
9. Top 10 Stocks by 30 Day % Change
10. Average Share Volume by Industry

---

## ✅ Key Insights
- 🏆 Top companies like [Insert Top 3 Companies from dataset] dominate market capitalization
- 🔥 Volatility analysis reveals potential high-risk, high-reward stocks
- 📊 Finance and IT sectors show higher trading activity and average prices
- 🔗 Strong correlation observed between previous close and last traded price

---

## 👩‍💻 Author
Shreya Das

📧 shreyadas0413@gmail.com

📱 https://www.linkedin.com/in/shreyadas1304/
