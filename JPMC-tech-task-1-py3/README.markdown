# Task 1: Interface with a stock price data feed
Interface with a stock price data feed and set up your system for analysis of the data

## Background Info:
You’ve been asked to assist with some development to add a chart to a trader’s dashboard allowing them to better identify under/over-valued stocks.

The trader would like to be able to monitor two historically correlated stocks and be able to visualize when the correlation between the two weakens (i.e. one stock moves proportionally more than the historical correlation would imply). This could indicate a potential trade strategy to simultaneously buy the relatively underperforming stock and sell the relatively outperforming stock. Assuming the two prices subsequently converge, the trade should be profitable.

We want to process the data feed of stock A and stock B’s price to enable us to analyse when trading for the stock should occur.

## Tasks Completed:
* implemented getDataPoint function to return correct tuple of stock name, bid_price, ask_price and price
* implemented getRatio function to return ratio of stock A's and stock B's prices
* made changes in main to output updated info
* implemented unit tests within client_test.py to check for discrepancies / bugs

![Result](result_task1.png)
![Result](result_task1 cont..png)
