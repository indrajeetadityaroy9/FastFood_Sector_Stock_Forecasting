# Stock Price Forecasting and Analysis of Fast Food Giants

Forecasting model to analyze and predict stock performance trends for 10 of the largest fast food companies. The dataset, collected from Yahoo Finance, consists of historical stock price data for companies such as McDonald’s (MCD), Starbucks (SBUX), and Yum! Brands (YUM). 

### Original Data Dictionary
| Column Name  | Data Type | Description                                           | Variable Type  | Type                  |
|--------------|-----------|-------------------------------------------------------|----------------|-----------------------|
| Date         | object    | The trading date       | Independent    | Categorical           |
| Open         | float   | The price at which the stock opened on a given day    | Independent    | Continuous Numerical  |
| High         | float   | The highest price of the stock during the trading day | Independent    | Continuous Numerical  |
| Low          | float   | The lowest price of the stock during the trading day  | Independent    | Continuous Numerical  |
| Close        | float   | The price of the stock at market close                | Independent    | Continuous Numerical  |
| Adj Close    | float   | Adjusted close price accounting for dividends/splits  | Dependent      | Continuous Numerical  |
| Volume       | int     | The number of shares traded during the day            | Independent    | Discrete Numerical    |
