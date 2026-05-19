# 📈 Stock Market EDA — India vs US Tech (2022–2024)

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA)** of historical stock market data from major **Indian** and **US technology companies**. The analysis was performed using **Python**, while the interactive dashboard was developed in **Power BI**.

The project aims to analyze:

* 📈 Stock price trends
* 💹 Daily returns
* 📉 Volatility
* 🔄 Moving averages
* 🔥 Correlation between stocks
* 📊 Portfolio diversification opportunities

Historical stock data was collected using the **yfinance API**.

---

# 📂 Table of Contents

* Project Overview
* Case Study
* Dataset Description
* Tech Stack
* Project Workflow
* Data Cleaning
* Exploratory Data Analysis
* Dashboard
* Key Findings
* Conclusion
* Future Improvements
* Author

---

# 📋 Case Study

The objective of this project is to compare the performance of leading **Indian** and **US stocks** between **2022–2024** and generate meaningful insights related to:

* Risk vs Return
* Market Volatility
* Sector-Wise Trends
* Diversification Opportunities
* Long-Term Market Performance

The project specifically compares **Indian IT stocks** with **US Tech giants** to understand how different markets behave over time.

---

# 📊 Dataset Description

## Stocks Used

| Market | Company                   | Ticker      |
| ------ | ------------------------- | ----------- |
| US     | Apple Inc.                | AAPL        |
| US     | Microsoft                 | MSFT        |
| India  | Reliance Industries       | RELIANCE.NS |
| India  | Tata Consultancy Services | TCS.NS      |
| India  | Infosys                   | INFY.NS     |

## Dataset Information

* 📅 Time Period: **2022 – 2024**
* 📌 Total Trading Days: **776**
* 📈 Total Stocks Analyzed: **5**
* 🌍 Markets Covered: **India & United States**

## Dataset Features

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Volume
* Daily Returns
* Moving Averages
* Volatility Metrics

---

# 🛠️ Tech Stack

| Tool / Library   | Purpose                    |
| ---------------- | -------------------------- |
| Python 3.13      | Core Programming           |
| Pandas           | Data Manipulation          |
| NumPy            | Numerical Computation      |
| yfinance         | Live Stock Data Extraction |
| Matplotlib       | Data Visualization         |
| Seaborn          | Statistical Visualization  |
| Jupyter Notebook | Development Environment    |
| Power BI         | Interactive Dashboard      |
| Git & GitHub     | Version Control            |

---

# 🔄 Project Workflow

### Step 1 — Data Collection

* Extracted historical stock data using the `yfinance` API
* Retrieved stock prices for Indian and US companies

### Step 2 — Data Cleaning

* Removed missing values using `dropna()`
* Standardized date formats
* Verified data consistency

### Step 3 — Exploratory Data Analysis

* Calculated daily returns
* Measured stock volatility
* Performed moving average analysis
* Conducted correlation analysis

### Step 4 — Dashboard Development

* Exported cleaned CSV files
* Built interactive Power BI dashboard
* Added KPI cards and analytical visuals

---

# 🧹 Data Cleaning

## Data Preprocessing Steps

* ✅ Fetched live OHLCV stock data using `yfinance`
* ✅ Removed missing/null values using `dropna()`
* ✅ Standardized date formats
* ✅ Checked trading-day consistency
* ✅ Exported cleaned CSV files for Power BI

---

# 🔍 Exploratory Data Analysis (EDA)

## 📈 Return Analysis

### Analysis Performed

* Computed daily returns using `pct_change()`
* Compared cumulative returns across all stocks
* Evaluated stock growth trends

### Key Insights

* 🚀 **MSFT** delivered the highest cumulative return (~50%)
* 📉 **INFY** showed the lowest cumulative growth (~5%)

---

## 📉 Volatility Analysis

### Formula Used

```python
Annualized Volatility = Daily Standard Deviation × √252
```

### Key Insights

* ⚠️ MSFT was the most volatile stock (~28.1%)
* 🛡️ TCS was the most stable stock (~20.7%)

---

## 📊 Moving Average Analysis

### Indicators Used

* 50-Day Moving Average
* 200-Day Moving Average

### Signals Identified

* 📈 Golden Cross
* 📉 Death Cross

These indicators helped identify bullish and bearish market trends.

---

## 🔥 Correlation Analysis

| Stock Pair      | Correlation | Insight                                 |
| --------------- | ----------- | --------------------------------------- |
| TCS & Infosys   | 0.73        | Strong positive correlation             |
| AAPL & MSFT     | 0.69        | Strong US tech movement                 |
| RELIANCE & MSFT | 0.09        | Weak correlation — good diversification |

### Key Insights

* Indian IT stocks moved similarly because of sector dependence
* US tech stocks showed strong alignment
* RELIANCE provided diversification benefits in the portfolio

---

# 📊 Power BI Dashboard

Built a professional and interactive dashboard using **Power BI**.

## Dashboard Visuals

| Visual                 | Chart Type        |
| ---------------------- | ----------------- |
| Stock Price Trend      | Line Chart        |
| Return Trend Analysis  | Area Chart        |
| Annual Volatility      | Bar Chart         |
| Portfolio Distribution | Donut Chart       |
| Volatility Comparison  | Stacked Bar Chart |
| Key Metrics            | KPI Cards         |

## Dashboard Features

* Interactive filters
* Stock-wise comparison
* Trend analysis
* Performance tracking
* Risk visualization

---

# 💡 Key Findings

* ✅ MSFT achieved the highest cumulative return
* ✅ TCS showed the lowest volatility and highest stability
* ✅ TCS & Infosys were highly correlated due to the Indian IT sector trend
* ✅ RELIANCE & MSFT had very weak correlation, making them suitable for diversification
* ✅ US tech stocks outperformed Indian stocks during the 2022–2024 period

---

# 📌 Conclusion

This project demonstrates how **Python-based EDA** and **Power BI dashboards** can be used together for financial market analysis.

The analysis helped in understanding:

* Market trends
* Risk management
* Portfolio diversification
* Comparative stock performance

This project also strengthened practical skills in:

* Data Cleaning
* Financial Analysis
* Data Visualization
* Dashboard Development
* Business Insight Generation

---

# 🚀 Future Improvements

* Add more Indian & US stocks
* Include sector-wise comparison
* Implement predictive modeling using Machine Learning
* Deploy dashboard using Power BI Service
* Add real-time stock market tracking

---

# 👨‍💻 Author

## Yash Ghormade

🎓 AIML Engineer
* LinkedIn-https://www.linkedin.com/in/yash-ghormade-35b238226/

* <img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/83bdeed9-9af3-4f70-9556-bc9fe726743b" />

The project analyzes:
- Stock Price Trends
- Daily Returns
- Volatility
- Moving Averages
- Correlation Analysis
- Portfolio Diversification



