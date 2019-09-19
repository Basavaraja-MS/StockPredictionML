##Predict the stock for the given company

The below work is made for the SkilanzaHackthon

#problem statement
Intraday trading deals with buying and selling of stocks on the same day, during the trading hours that are stipulated by the exchange. Stocks are bought and sold in large numbers strategically with the intention of booking profits in a day.

You need to build a product an intraday trader can use after the market is live to predict the closing price for the same day. This is because the closing price is one of the most important features for intraday traders.

To help with your predictive model, realise that you can find relational dependencies between stocks like Samsung electronic stocks that might be impacted by Samsung R&D.

You can also use tweets and blogs, posts of top traders and CEOs of companies to find the impact on closing price.

To extract tweets, you can use an API from Twitter called tweepy. For other data extraction, use Python APIs like Beautiful Soup or Selenium.

This is the format of the data:

Date
Open
High
Low
Close*
Adj. close**
Volume
You can download data from Yahoo! Finance: https://in.finance.yahoo.com/

You can even directly download the file in csv format.
https://in.finance.yahoo.com/quote/005930.KS/history?p=005930.KS
