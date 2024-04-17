# MAIN finding
* Correlation Analysis: The trading volume showed a significantly high positive correlation with Open, High, Low, Close, and Adjusted Close prices. This suggests that trading volume is closely associated with price fluctuations.

* Linear Regression Analysis: Upon dividing the data into varying ratios for testing, it was observed that the R^2 values were inconsistent across both the training and test sets. This indicates that linear regression models have limitations in predicting price volatility.

* Decision Trees and SVM: Given the high MSE values and low R^2 values, both decision trees and SVM did not perform as expected in the test sets.

* Graph Patterns: Although the numerical data did not provide satisfactory explanatory power, graph analysis revealed that trading volume significantly increases the range of variability.

------
# Narrative story

My analysis was an attempt to grasp the relationship between trading volume and price volatility within the intricate realm of the stock market. My initial hypothesis posited that trading volume could act as a significant indicator for predicting price volatility. However, throughout my analysis, I came to realize that this relationship was more complex than initially anticipated. Notably, despite employing supervised learning algorithms such as linear regression, decision trees, and SVM, I found these models to be limited in their capacity to adequately explain or forecast price volatility. Conversely, when I applied the unsupervised learning algorithm, k-means clustering, I was able to identify specific patterns. This suggests that while trading volume may not directly predict price volatility, it could assist in forecasting the range of volatility.