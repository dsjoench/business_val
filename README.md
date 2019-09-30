# Investment portfolio/Risk management (Ongoing project)

This portfolio,combining with a Excel-based portfolio, aim to build an algorithmic trading by analyzing investment portfolio and time series data to optimize overall return. Later I will post a video on each steps I did.

The codes shown in this respository built in python, along with some object oriented programming to automate time series analysis procedure.

1. Import data/ manupulate data so that users can flexibly adjust parameter such as stock index, data range to scope in financial data.
2. Data  visualization on moving average, standard deviation,etc
3. Highlight informative attributes to generate signals to forecast future stock price via various machine learning algorithms
4. Conduct financial analysis to turn financial statements into actions.



First, you need to decide on the stocks/ funds you want to invest in. Second, you need to decide the timeframe of the holidng period. Is it a short-term trading or a long-term investment. Here are the breakdown of the files:

Financial Analysis: I utilize BeautifulSoup to extract financial data from Yahoo Finance. Since They update the web format once in a while, I have built two different versions to have a clear automated importing and cleaning process.

Time series: Here you can adjust the parameter of stock symbol and date range to compare with the SP500 and NASDAQ performance. It plots the stock price movement,moving averages, daily violatility, compared with the market performance. It shows correlation between the stock and the market. I also did hypothesis testing to show the strength of the movements.

algorithmic trading: Here I implemented a few trading strategies combining with predicted stock price in a portfolio, optimized by regression model, and other models yet to be implemented.
