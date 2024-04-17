# DATA
[**The numerical value of correlation**](initial_exploration.ipynb) click, you can see the data manipulation in the early part of this project. In this section, you can check the correlation of data represented in numbers and float types. If you look at the correlation between the main variables of my project, Volume and High, it being 0.727335 means it has an explanatory power of about 73%.

-----
[**The result of linear regression for train and test set**](linear_regression.ipynb)This link is about the process of analyzing and predicting the relationship between the 'Volume' and 'High' variables in a dataset using a Linear Regression model. The dataset is already cleaned, and the train_test_split function from sklearn is used to divide it into training and test sets. The model is trained to predict 'High' using 'Volume' as the independent variable, and its predictive performance is evaluated using the R-squared value and RMS error. This link discusses the explanatory power of the model, prediction errors, and the impact of adjusting the ratio of the training set to the test set on model performance.

-----
[**Clustering Part**](classification.ipynb)This content is about the process of creating a regression model to predict the highest price based on trading volume using Bitcoin price data. It explains that there are no missing values in the dataset, and all values are numeric except for 'Date'. The target variable (y) is chosen as 'High' (the highest price) to explain price increases, and the predictor variable (x) is 'Volume' (trading volume). Subsequently, analysis is conducted using Decision Tree and SVM (Support Vector Machine), and the results are evaluated to discuss the interpretative power and prediction accuracy of the regression model.

-----
[**The linear regression results**](linear.png) That shows as the volume getting increased, the lowest price getting increased.

-----
[**This is result of supervised learning algorithm**](supervised.png) that is one of the supervised algorithm. No pattern.

-----
[**This is the result of kmean cluster**](kmean_clust.png) That shows the Fluctuation range is getting wider as the volume increase. 

[Back to Readme](README.md)