[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents
* Project Overview: The main objective of the project is to predict the price of Bitcoin by identifying the variables that best explain its price among various features and performing the prediction.
* Dataset: BTC-USD.csv is a dataset that includes weekly data from January 15, 2015, to December 31, 2023. It contains features such as 'Date', 'Open', 'High', 'Low', 'Close', 'Adj Close', 'Volume', and 'fluctuation rate'. The dataset consists of 470 data points.
---------
## Result of Project Proposal 1
* r2_test: 0.4999218786939512
* r2_train: 0.5330701593853446
* rms_error: 114989706.75567454
* rms_error_train: 148072271.52454865
* r2_test1: 0.6243973120733342
* r2_train1:0.5194235460488409
* rms_error1: 88247865.34693414
* rms_error_train1: 147468964.15932348
* If R-squared (r2) and Root Mean Square Error (RMSE) values are low in an excellent model, it implies insufficient explanatory power for the 'Volume' and 'High' variables. In other words, these variables are not effectively explaining the fluctuations in Bitcoin prices.