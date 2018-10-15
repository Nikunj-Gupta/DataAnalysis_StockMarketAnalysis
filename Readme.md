# Data Analytics

# Business Understanding Document

## Problem Domain 
Stock market. 

## Target Audience 
Investors and Traders in stock market.

## Goal
By analysing the given data we help investors and traders to make buying and selling
decisions in a way to gain an edge in the market.

## Current (Existing) Solution 
Currently, to make any investment decision we are relying on stock brokers who provide us
the current trends happening in the market which include their opinions. Based on their
inputs we invest/buy or sell shares. With our approach we can minimise the role of stock
brokers. This helps the users to know the trends in the market and also make unbiased
decisions.

## Resources 

● Data Set:
○ The data set consists of two csv files - “instruments.csv” and “log.csv”.
○ The “instruments.csv” file contains attributes which describe about various
stocks. The “log.csv” file contains transaction data based on the depth and
timestamp of the stocks.
○ The “log.csv” file contains transactions that were recorded for a period of
three days. It also has some depth parameters which show the supply and
demand for stock at various prices and can be an indicator of market
sentiment.

● Initial Assessment Tools and Techniques:
○ R
○ Tableau

## Business Understanding ​
● **Exploratory Analysis** ​​: Find Support level and resistance level of a stock. Support
level is a price level at which the stock might find support and below which it may not
fall. In contrast, a resistance level is a price at which the stock might find pressure
and above which it may not rise.

● **Descriptive Analysis** ​​: Summary of a particular stock based on the selling and
buying quantity of that stock. This can be shown in the form of bar charts, box plots,
pivot tables, etc.

● **Classification** ​​: Based on quantity of a particular stock sold compared to quantity of
that stock bought in a particular time period, we classify it as a buying trend or selling
trend.

● **Clustering** ​​: Clustering can be done on various attributes like strike rate, average
price, sell price, etc. This can help us in forming clusters which tell us about the
profits or budget. The dataset has some depth parameters too. Clustering can be
done on them to obtain some results.

● **Association** ​​: If the values of the raw inputs required for a particular company change
(increase or decrease) then it will affect the share price of that company. For
example, if rubber becomes cheaper, then the manufacturing price of tyres will fall
leading to increase in the prices of shares of a tyre producing company. Association
can be possible after we obtain some clusters as described before.

## Assumptions
● We assumed that this is the real world data. ​The data gives Real-world data for half
of the Nifty 50 stocks for last week of May and first 2 Weeks of July.

● All the data points are not tick-by-tick update. Rather it is mostly an update after 600
ms, provided a trade happened.

## Constraints
In the collected dataset, information about the stock like to which sector (consumer-goods,
IT sector, financial,banking) it belongs is not given. So, analytics based on sector may not be
possible.

## Risks 
This type of data analytics comes under Technical analysis which assumes that, market
value of a stock depends solely on the supply-demand which is reflected in the past trading
patterns. So, our inference model is only capable of predicting the support and resistance
values based on these trends. But, in real-world, investments are subject to market risks.
They depend on various other factors like sentiments, reputation, politics etc.

## References 
https://www.kaggle.com/deeiip/1m-real-time-stock-market-data-nse/data



