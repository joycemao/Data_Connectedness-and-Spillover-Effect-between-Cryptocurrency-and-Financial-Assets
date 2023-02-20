# Title of Dataset
# Connectedness-and-Spillover-Effect-between-Cryptocurrency-and-Financial-Assets Data
Datas used in &lt;Connectedness and Spillover Effect between Cryptocurrency and Financial Assets>
## This repository contains two CSV files that are used in the analysis of the paper "Connectedness and Spillover Effect between Cryptocurrency and Financial Assets". The data is available for public use and includes information on stock returns and volatility returns.
#### The study downloads cryptocurrencies and other financial assets data through the price information website investing.com. We wrote a letter to the source website to inquire whether it is possible to use the data for analysis and writing a paper, and received a positive response.
#### We collect price data of the daily transaction. The data period is from November 2017 to February 2022. Cryptocurrencies are traded 24 hours a day. However, stock, bonds, and other financial assets are traded only on business days. We exclude the transaction data of the stock market close day. As a result, we obtain 1087 price data of cryptocurrency and other assets. The return rate is calculated by taking the price to one order difference. Volatility is calculated in the same way as studied by Diebold and Yilmaz (2012), estimated by subtracting the maximum and minimum prices of the day.

## Description of the data and file structure
## The two CSV files in this repository are named "return.csv" and "volatility.csv". The "return.csv" file contains the stock return data used in the paper, while the "volatility.csv" file contains the volatility return data. The data is organized by date and includes the following columns:
#### Date: the date of the observation
#### BTC	: the daily returns of Bitcoin
#### ETH	: the daily returns of Ether
#### BNB	: the daily returns of Binance
#### CCI30	: the daily returns of  CCI30 Index
#### SP500	: the daily returns of US S&P 500 Index
#### DJI	: the daily returns of Dow Jones Industrial Average
#### Nas100	: the daily returns of Nasdaq100 US Technology Industry Index
#### US10Y	: the daily returns of US 10-year Treasury Yield
#### Gold	: the daily returns of Dow Jones Commodity Gold Index
#### Engergy	: the daily returns of Dow Jones Commodity Energy Index
#### Metal : the daily returns of Dow Jones Commodity Industrial Metals Index
#### The "volatility.csv" file includes the volatility data used in the analysis. It has the same format as the "return.csv" file, but includes the daily volatility of each asset.

## Sharing/Access information
#### we wrote a letter to inquire whether it is possible to use the data from the source website for analysis and writing a paper, and received a positive response.
#### the source website : https://www.investing.com/ 
