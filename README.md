[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/7lKBcjfN)
# 44-566 machine-learning project
Repo for all project documents
* **Project Overview**: The main objective of the project is to predict the price of Bitcoin by identifying the variables that best explain its price among various features and performing the prediction.
* **Dataset**: BTC-USD.csv is a dataset that includes weekly data from January 15, 2015, to December 31, 2023. It contains features such as 'Date', 'Open', 'High', 'Low', 'Close', 'Adj Close', 'Volume', and 'fluctuation rate'. The dataset consists of 470 data points.
---------
# The link to other main sctions listed for the submission.
1. [RAW_DATA](RAW_DATA.md)
1. [DATA](DATA.md)
1. [ANALYSIS](ANALYSIS.md)
1. [CONCLUSIONS](CONCLUSION.md)
---------
# Introduction
* **Initial goals**: The initial goal of this project was to prove that Bitcoin's price can be predicted based on its trading volume using various algorithms.
* **Narrative conclusion**: Through this project, we aimed to explain the predictive power of trading volume on price using various algorithms. However, we were unable to obtain significant r-squared values with algorithms such as linear regression, Decision Tree, and SVC. Nevertheless, the scatter plot from linear regression showed us that as trading volume increases, the price's lowest points tend to rise. Furthermore, our data ultimately produced results with the unsupervised learning algorithm, k-means. The scatter plot from k-means revealed a meaningful pattern: as trading volume increases, the price's fluctuation range becomes wider. Ultimately, I learned that as trading volume increases, so does volatility.
----------
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
## Result of Project Milestone 2
#### Decision Tree:
* r2_train:1.0
* mse_train:28237608.853999097
* r2_test:1.0
* mse_test:179664678.10349232
#### SVM:
* r2_train_svm:1.0
* mse_train_svm:367634501.22843015
* r2_test_svm:1.0
* mse_test_svm:255988430.89353034
#### summary
* Both Decision Tree and SVM models achieved perfect R-scores of 1.0 on both the training and test sets. However, when it comes to Mean Squared Error (MSE), the Decision Tree model had a much lower value on the test set (179,664,678.103), indicating better performance in terms of prediction accuracy compared to the SVM model (255,988,430.894). Despite the high R-scores indicating excellent explanatory power, the high MSE values suggest that the models may have significant errors when making predictions, particularly the SVM model.

