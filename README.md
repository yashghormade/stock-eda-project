Financial Stock Trend EDA

Table of Content
Case Study
Dataset Description
Data Cleaning
Data Analysis
Dashboard

Case Study
Stock market analysis of 5 major companies (Reliance, TCS, Infosys, Apple, Microsoft) using real historical data from 2022–2024, including stock prices, daily returns, volatility, and correlation patterns across Indian and US markets.

Dataset Description
Our dataset consists of the following observations:

Stock Data (stock_data.csv)
Date - Trading date
AAPL - Apple Inc. closing price (USD)
INFY.NS - Infosys closing price (INR)
MSFT - Microsoft closing price (USD)
RELIANCE.NS - Reliance Industries closing price (INR)
TCS.NS - TCS closing price (INR)

Stock Returns (stock_returns.csv)
Date - Trading date
AAPL - Apple daily return
INFY.NS - Infosys daily return
MSFT - Microsoft daily return
RELIANCE.NS - Reliance daily return
TCS.NS - TCS daily return 


Data Cleaning
Steps to fetch data:
Used yfinance library to fetch live historical data
Downloaded 776 days of OHLCV data (2022–2024)
Handled missing/null values using dropna()
Exported clean data to CSV for Power BI

Data Analysis
Return Analysis:

Computed daily percentage returns using pct_change()
MSFT delivered highest cumulative return (~50%)
INFY delivered lowest return (~5%)

Volatility Analysis:

Annualized volatility = daily std × √252
MSFT most volatile at 28.1%
TCS most stable at 20.7%

Moving Averages:

Computed 50-day and 200-day moving averages
Used to identify Golden Cross and Death Cross signals

Correlation Analysis:

TCS & Infosys highly correlated (0.73) — Indian IT sector
AAPL & MSFT correlated (0.69) — US Tech sector
Reliance & MSFT nearly independent (0.09) — good for diversification

🛠️ Tech Stack: Python | Pandas | NumPy | yfinance | Matplotlib | Seaborn | Power BI | Jupyter Notebook

👨‍💻 Author
Yash Ghormade
🔗 GitHub | 💼 Open to Data Analyst
