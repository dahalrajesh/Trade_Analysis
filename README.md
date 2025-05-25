# Trade_Analysis
Overview

This repository contains my submission for the Junior Data Scientist assignment at PrimeTrade.ai. The goal of this project is to explore the relationship between Bitcoin market sentiment (Fear/Greed) and trader performance using historical data from the Hyperliquid platform.


Objectives
Merge Bitcoin Fear & Greed Index data with trader execution data

Analyze how market sentiment impacts:
Closed PnL (profit/loss)
Trade size and leverage
Frequency and nature of trades
Discover behavioral patterns and performance trends
Generate actionable insights for smarter trading strategies

Datasets Used
Historical Trader Data (Hyperliquid)
Fields: account, symbol, execution price, size, side, time, start position, event, closedPnL, leverage, etc.
Bitcoin Market Sentiment Data
Fields: Date, Classification (Fear or Greed)

Methods
Data cleaning and preprocessing (datetime parsing, type casting)
Merging datasets on timestamp/date
Exploratory data analysis (EDA) using:
Univariate, bivariate, and multivariate visualizations
Grouped analysis by sentiment and performance metrics
Insight generation and interpretation

Key Insights
1.Market sentiment influences trading behavior but not always profitability
2.Fear leads to more trades and strategy variance, but profits are inconsistent
3.Greed phases tend to favor SELL strategies — likely due to overbought conditions
4.Time of day and sentiment together significantly impact performance
5.The Fear-Greed Index is an effective market mood classifier

Tools & Libraries
Python, Pandas, NumPy
Matplotlib, Seaborn, Plotly
Jupyter Notebook

Conclusion
The analysis shows tangible links between market sentiment and trading behavior. Traders appear more profitable and confident during Greed periods. These insights can support real-time strategy adaptation and improved risk management in Web3 trading environments.
