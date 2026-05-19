📈 Stock Market EDA — India vs US Tech (2022–2024)
📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on historical stock market data from leading Indian and US technology companies.
Using Python and Power BI, the project analyzes:

Stock price trends
Daily returns
Volatility
Moving averages
Correlation between stocks
Portfolio diversification opportunities

The dataset was collected using the yfinance API and includes data from both NSE (India) and NASDAQ (US) markets.

📂 Table of Contents
Project Overview
Case Study
Dataset Description
Tech Stack
Project Workflow
Data Cleaning
Exploratory Data Analysis
Dashboard
Key Insights
Conclusion
Future Improvements
Author

📋 Case Study

The objective of this project is to compare the performance of major Indian and US stocks between 2022–2024 and derive meaningful insights related to:

Risk vs Return
Market volatility
Sector-wise movement
Diversification opportunities
Long-term trend analysis

The project focuses on both Indian IT stocks and US Tech giants to understand how different markets behave under varying economic conditions.

📊 Dataset Description
Stocks Used
Market	Company	Ticker
US	Apple Inc.	AAPL
US	Microsoft	MSFT
India	Reliance Industries	RELIANCE.NS
India	Tata Consultancy Services	TCS.NS
India	Infosys	INFY.NS
Dataset Information
📅 Time Period: 2022 – 2024
📌 Total Trading Days: 776
📈 Total Stocks Analyzed: 5
🌍 Markets Covered: India & United States
Features Included
Date
Open Price
High Price
Low Price
Close Price
Volume
Daily Returns
Moving Averages
Volatility Metrics
🛠️ Tech Stack
Tool / Library	Purpose
Python 3.13	Core Programming
Pandas	Data Manipulation
NumPy	Numerical Computation
yfinance	Live Stock Data Extraction
Matplotlib	Data Visualization
Seaborn	Statistical Visualization
Jupyter Notebook	Development Environment
Power BI	Interactive Dashboard
Git & GitHub	Version Control
🔄 Project Workflow
Extracted historical stock data using yfinance
Cleaned and preprocessed the dataset
Calculated daily returns and volatility
Performed moving average analysis
Conducted correlation analysis between stocks
Built an interactive Power BI dashboard
Derived business insights and investment observations
🧹 Data Cleaning
Data Preprocessing Steps
✅ Fetched live OHLCV stock data using yfinance
✅ Removed missing/null values using dropna()
✅ Standardized date formats
✅ Verified trading-day consistency
✅ Exported cleaned CSV files for Power BI analysis
🔍 Exploratory Data Analysis (EDA)
📈 Return Analysis
Calculated daily returns using pct_change()
Compared cumulative returns across all stocks
Identified best and worst performers
Key Observation
🚀 MSFT delivered the highest cumulative return (~50%)
📉 INFY showed the lowest overall growth (~5%)
📉 Volatility Analysis

Annualized volatility calculated using:

σ
annual
	​

=σ
daily
	​

×
252
	​


Key Observation
⚠️ MSFT was the most volatile stock (~28.1%)
🛡️ TCS was the most stable stock (~20.7%)
📊 Moving Average Analysis

Computed:

50-Day Moving Average
200-Day Moving Average
Signals Identified
📈 Golden Cross
📉 Death Cross

These indicators helped identify possible bullish and bearish market trends.

🔥 Correlation Analysis
Stock Pair	Correlation	Insight
TCS & Infosys	0.73	Strong positive correlation
AAPL & MSFT	0.69	Strong US tech sector movement
RELIANCE & MSFT	0.09	Weak correlation — good diversification
Key Insight
Indian IT stocks moved similarly due to sector dependence
US tech stocks showed strong market alignment
RELIANCE provided diversification benefits
📊 Power BI Dashboard

Developed an interactive dashboard with professional visualizations.

Dashboard Visuals
Visual	Chart Type
Stock Price Trend	Line Chart
Return Trend Analysis	Area Chart
Annual Volatility	Bar Chart
Portfolio Distribution	Donut Chart
Volatility Comparison	Stacked Bar Chart
Key Metrics	KPI Cards
Dashboard Features
Interactive filters
Stock-wise comparison
Trend analysis
Performance tracking
Risk visualization
💡 Key Findings
✅ MSFT achieved the highest cumulative return
✅ TCS showed the lowest volatility and highest stability
✅ TCS & Infosys moved closely due to the Indian IT sector trend
✅ RELIANCE & MSFT had minimal correlation, improving diversification
✅ US tech stocks outperformed Indian stocks during 2022–2024
📌 Conclusion

This project demonstrates how Python-based EDA and Power BI dashboards can be combined to analyze financial markets effectively.

The analysis highlights:

Market trends
Risk management
Portfolio diversification
Comparative stock performance

This project also strengthened practical skills in:

Data Cleaning
Financial Analysis
Visualization
Dashboard Development
Business Insight Generation
🚀 Future Improvements
Add more Indian & US stocks
Include sector-wise comparison
Perform predictive modeling using Machine Learning
Deploy dashboard online using Power BI Service
Add real-time stock tracking
👨‍💻 Author
Yash Ghormade
🎓 AIML Engineer
📊 Aspiring Data Analyst
💼 Open to Internships & Entry-Level Opportunities
🔗 Connect With Me
