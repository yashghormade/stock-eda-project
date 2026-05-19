📂 Table of Contents

Case Study
Dataset Description
Tech Stack
Data Cleaning
Data Analysis & Insights
Dashboard
Key Findings


📋 Case Study
Real historical stock data fetched using yfinance API, analyzing price trends, daily returns, volatility, and inter-stock correlations across Indian (NSE) and US markets.

📊 Dataset Description
ColumnDescriptionDateTrading dateAAPLApple Inc. closing price (USD)MSFTMicrosoft closing price (USD)RELIANCE.NSReliance Industries closing price (INR)TCS.NSTCS closing price (INR)INFY.NSInfosys closing price (INR)
Total Records: 776 trading days | 5 Stocks | 2 Markets

🛠️ Tech Stack
ToolPurposePython 3.13Core programmingPandas & NumPyData manipulationyfinanceLive data extractionMatplotlib & SeabornData visualizationJupyter NotebookDevelopment environmentPower BIInteractive dashboardGitHubVersion control

🧹 Data Cleaning

Fetched live OHLCV data using yfinance
Handled missing values using dropna()
Exported clean CSV files for Power BI


🔍 Data Analysis & Insights
📈 Return Analysis

Computed daily returns using pct_change()
MSFT delivered highest cumulative return (~50%)
INFY delivered lowest return (~5%)

📉 Volatility Analysis

Annualized volatility = daily std × √252
MSFT most volatile — 28.1%
TCS most stable — 20.7%

📊 Moving Averages

Computed 50-day and 200-day moving averages
Identified Golden Cross and Death Cross signals

🔥 Correlation Analysis
Stock PairCorrelationInsightTCS & Infosys0.73Strong — both Indian ITAAPL & MSFT0.69Strong — both US TechRELIANCE & MSFT0.09Independent — good for diversification

📊 Dashboard
Built using Power BI with 6 professional visuals:
VisualChart TypeStock Price TrendLine ChartReturn Trend AnalysisArea ChartAnnual VolatilityBar ChartPortfolio DistributionDonut ChartVolatility ComparisonStacked BarKey MetricsKPI Cards

💡 Key Findings
✅ MSFT best performer — ~50% cumulative return
✅ TCS most stable stock — lowest volatility
✅ TCS & Infosys highly correlated — Indian IT sector moves together
✅ RELIANCE & MSFT nearly independent — ideal portfolio combination
✅ US stocks outperformed Indian stocks in 2022–2024 period

👨‍💻 Author
Yash Ghormade
🔗 GitHub | 💼 Open to Data Analyst Internships
