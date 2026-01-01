# 📊 Stock Data Web Scraping & Visualization (Groww)

## 📌 Project Overview
This project focuses on **scraping live stock market data** from the Groww website and presenting it through **cleaned, structured data and visualizations**.

The objective is to demonstrate how real-world financial data can be:
- Collected using web scraping
- Cleaned to handle inconsistent numeric formats
- Visualized to compare stock prices, trading volumes, and short-term price changes

> ⚠️ This project focuses on data collection, cleaning, and visualization. It is **not a full Exploratory Data Analysis (EDA)** project.

---

## 🛠️ Tools & Technologies
- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib

---

## 📂 Data Collected
The following data points are scraped from Groww for each stock:
- Company Name
- Current Stock Price (₹)
- 1-Day Price Change (%)
- Trading Volume

Data is extracted directly from individual stock pages.

---

## 🧹 Data Cleaning
Real-world financial data often appears in mixed formats such as:
- `1,23,456`
- `2.5K`
- `1.2M`
- `0.8Cr`
- `NaN`

A custom volume conversion function was implemented to:
- Remove commas
- Convert `K`, `M`, and `Cr` into numeric values
- Handle missing or invalid values safely
- Standardize all volume data into numeric format

---

## 📈 Visualizations
The project includes the following visualizations:

### 1️⃣ Stock Price Comparison
- Compares current stock prices across selected companies
- Highlights price differences across sectors

### 2️⃣ Trading Volume Comparison
- Displays trading volume to identify liquidity and market activity
- Helps identify actively traded stocks

### 3️⃣ Volume vs 1-Day Price Change
- Compares trading volume with daily price movement
- Shows that high trading volume does not always result in high price change

---

## 🧠 Key Insights
- Trading volume indicates liquidity and investor interest
- High-priced stocks are not necessarily the most actively traded
- Volume and short-term price movement are related but not strongly correlated
- Data cleaning is critical when working with scraped financial data

---
