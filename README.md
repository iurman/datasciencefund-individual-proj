
# AAPL-Stock-Performance-Analysis-Individual-Project

Isaac Urman

Professor Weiji Pang

COMP 3125

12/3/2023

Individual Project

## Introduction
In the financial markets, individual stocks can dramatically impact an investment portfolio, much like star players in a sports league. Apple Inc., as a leading tech company, has had significant influence due to its market capitalization and popularity among investors. This research aims to analyze the performance and trading behavior of AAPL stock over several years to uncover patterns, trends, and anomalies that could inform future investment strategies.


## Datasets
The data for this analysis was sourced from Kaggle, **"Huge Stock Market Dataset"** with a thorough validation to ensure their reliability. The primary datasets for this study are **"combined_stock_prices.csv"**, which includes data such as stock tickers, daily opening and closing prices, volume, and open interest. The data was imported, cleansed, and prepared for analysis. I will primarily use **"aapl.us.txt"** to analyze specifically AAPL's historical record of stock prices.

## Methodology
**Pandas** was used to manipulate and analyze the time-series data, while Matplotlib was used to visualize price movements and trading signals.

**Tools:**

The analysis of AAPL's stock performance was conducted using a variety of tools tailored for data analysis, visualization, and machine learning. These included:

- NumPy and Pandas for data manipulation and analysis.
- Matplotlib for data visualization to illustrate stock trends, volatility, and trading signals.
- Jupyter Notebooks as an interactive computational environment where the analysis was performed.

**Data Analysis Methods:**

The analysis primarily focused on time-series data, employing methods such as:

- Trend Analysis: Utilizing moving averages to identify long-term trends in AAPL's stock price.
- Volatility Estimation: Using Exponentially Weighted Moving Averages (EWMA) to measure stock price volatility over time.
- Momentum Indicators: Calculating the Moving Average Convergence Divergence (MACD) to understand momentum and potential trading signals.
- Volume Analysis: Identifying days with anomalously high trading volume, which may indicate significant market events.


### Questions asked:

1. How has AAPL's stock price *trend* developed over time, and what does the *residual analysis* reveal about anomalies in its price movements?
2. What does the *Moving Average Convergence Divergence (MACD)* indicate about AAPL's price momentum and potential buy/sell signals?
3. How has AAPL's stock price volatility, as estimated by the *Exponentially Weighted Moving Average (EWMA)*, changed over time?
4. How effective is the *Simple Moving Average (SMA)* Crossover Strategy in identifying potential trading signals for AAPL?
5. Can we identify *significant* trading days for AAPL with unusually high volume, and what might these indicate about market behavior?


## Results
The results from the analysis were insightful and, at times, surprising, offering a comprehensive view of AAPL's stock behavior.

**Question 1's results:**
- The trend analysis showed a long-term upward trajectory for AAPL, with a notable increase in price movement starting in the early 2000s. Residuals increased in parallel, indicating heightened periods of volatility.
[Time Series Decomposition](graph/question1.png)

**Question 2's results:**
- The MACD analysis revealed frequent and pronounced crossovers in the recent decade, reflecting periods of strong momentum. This could help investors time their market entries and exits.
[Moving Average Convergence Divergence (MACD)](graph/question2.png)

**Question 3's results:**
- Volatility analysis using EWMA highlighted several periods of high volatility, particularly around the early 2000s and the 2008 financial crisis, after which volatility showed a general declining trend.
[Volatility Modeling with EWMA](graph/question3.png)

**Question 4's results:**
- The SMA Crossover Strategy visualization indicated that while there were several accurate signals for market entry and exit points, the strategy also had limitations due to the lagging nature of SMAs.
[Simple Moving Average Crossover Strategy](graph/question4.png)

**Question 5's results:**
- Volume analysis identified several days with trading volumes significantly above the average, which could be linked to major company events, product announcements, or other market-moving news.
[Volume Analysis - Identifying Anomalous Trading Days](graph/question5.png)

## Discussion
### What do these results indicate about AAPL's stock?
The comprehensive analysis suggests that AAPL has shown robust growth over time, with clear periods of increased investor interest and market activity. The stock shows strong momentum, punctuated by periods of heightened volatility which coincide with significant company and market events.
### What would I change in the future for this topic?
For future research, incorporating additional data such as earnings reports, product launch dates, and macroeconomic indicators could provide even deeper insights into the causes behind the stock's price movements and trading volume spikes.

## References
[1] [Huge Stock Market Dataset](www.kaggle.com/datasets/borismarjanovic/price-volume-data-for-all-us-stocks-etfs)

[2] [Decomposition Models](https://online.stat.psu.edu/stat510/lesson/5/5.1/0)

[3] [Exponentially Weighted Moving Average](https://www.investopedia.com/articles/07/ewma.asp)

[4] [Simple Moving Average Crossovers](https://www.schwab.com/learn/story/understanding-simple-moving-average-crossovers)

[5] [MACD](https://www.fidelity.com/learning-center/trading-investing/technical-analysis/technical-indicator-guide/macd)
