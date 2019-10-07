# Investment portfolio/Risk management (Ongoing project)

This portfolio,combining with a Excel-based model, aim to analyze investment decision and time-series data to optimize  return and risk. Later I will post a video on each steps I took.

The codes shown in this respository are built in python, with some object-oriented programming to automate time series analysis procedure.

1. Import data/ manupulate data so that users can flexibly adjust parameter such as stock index, data range to scope in financial data.
2. Data  visualization on moving average, standard deviation,etc
3. Highlight informative attributes to generate signals to forecast future stock price via various machine learning algorithms
4. Conduct financial analysis to turn financial statements into actions.



First, you need to decide on which stocks or funds you want to invest in. Second, you need to decide the holdng period. Is it a short-term trading or a long-term investment? 

Here are the breakdown:

Financial Analysis: I utilized the package BeautifulSoup to extract financial data from Yahoo Finance. Since the website update the layout from time to time, I have built two different versions to tackle this problem so that we can have a cleaner automatic importing and cleaning process.

Time-series analysis: Users can adjust the parameter of individual stock symbol and date range to compare with the SP500 and NASDAQ's performance. The scripts will plot the stock price movement,moving average, daily violatility, etc, comparing with the market performance. It shows correlation between the stock price and the market movements. Hypothesis testing is also used to show the strength of their relationships.

Trading strategy: Trading strategies were implemented by predicting future stock price. The optimized parameters are optimized by the regression model, and other models yet to be implemented.
