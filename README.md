Trader Behavior and Market Sentiment Analysis:

Project Overview:
This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and trader behavior using Hyperliquid historical trading data. The objective of this analysis is to understand how market sentiment influences trading activity, trading direction, trader participation, and profitability patterns.

Datasets Used:

1. Bitcoin Market Sentiment Dataset:
Contains daily market sentiment classifications:
Extreme Fear
Fear
Neutral
Greed
Extreme Greed

2. Hyperliquid Historical Trader Dataset:
Contains trader activity information such as:
Account
Coin/Symbol
Execution Price
Trade Side
Trade Size
Event Type
ClosedPnL
Timestamp

---

Project Workflow:

Data Loading and Inspection
Imported datasets using pandas
Checked dataset dimensions
Identified missing values and duplicate records
Explored column names and data types

Data Cleaning and Preprocessing:
Converted timestamp columns into datetime format
Extracted date information from timestamps
Standardized date formats across datasets
Removed unnecessary columns where required

Dataset Merging:
Merged both datasets using the Date column
Created a unified dataset for sentiment-based trader analysis

Exploratory Data Analysis (EDA)
Performed detailed analysis on:
Market sentiment distribution
Number of trades per day
Buy/Sell activity distribution
Long/Short trading behavior
ClosedPnL analysis
Trader participation trends
Sentiment-based trading activity

Data Visualization:
Created visualizations using matplotlib and seaborn:
Count plots
Bar charts
Distribution plots


Trader Behavior Analysis:
Analyzed trader behavior across different market sentiment conditions by comparing:
Trade frequency
Directional trading behavior
Buy/Sell activity
Long/Short distribution
Profitability trends

---

Technologies Used:
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

---

Key Insights:
Trader behavior changes significantly across different market sentiment conditions.
Greed periods generally show higher trader participation and bullish trading activity.
Fear periods reflect comparatively cautious trading behavior.
Trading direction and activity vary depending on overall market sentiment.
Market sentiment influences trading participation and profitability patterns.

