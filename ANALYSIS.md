# Metrics
## correlation
                      Open      High       Low     Close  Adj Close    Volume  \
Open              1.000000  0.996422  0.994347  0.991463   0.991463  0.715169   
High              0.996422  1.000000  0.994708  0.996608   0.996608  0.727335   
Low               0.994347  0.994708  1.000000  0.996758   0.996758  0.692704   
Close             0.991463  0.996608  0.996758  1.000000   1.000000  0.709514   
Adj Close         0.991463  0.996608  0.996758  1.000000   1.000000  0.709514   
Volume            0.715169  0.727335  0.692704  0.709514   0.709514  1.000000   
fluctuation rate -0.091587 -0.041990 -0.038023 -0.002386  -0.002386 -0.042953   
                  fluctuation rate  
Open                     -0.091587  
High                     -0.041990  
Low                      -0.038023  
Close                    -0.002386  
Adj Close                -0.002386  
Volume                   -0.042953  
fluctuation rate          1.000000
[link](initial_exploration.ipynb)

----------
## Linear regressions
* splite by 0.2
 - test: 0.4999218786939512, mse: 114989706.75567454
 - train: 0.5330701593853446,mse: 148072271.52454865
* splite by 0.1
 - test: 0.6243973120733342,mse: 88247865.34693414
 - train:0.5194235460488409,mse: 147468964.15932348
[link](linear_regression.ipynb)

--------
## DecisionTreeRegressor and SVM
- train:0.910955764602079,mse: 28237608.853999097
- test: 0.21865724136550446,mse 179664678.10349232
- The R score and MSE of test set from decision tree:  0.21865724136550446 179664678.10349232
- The R score and MSE of test set from SVM:  1.0 255988430.89353034

-------
## MLPRegressor
- MSE for mlpregressor: 123191946.24168992
- R2: 0.4642512032187618
-------
# Challenge
* As indicated by the results, many metrics did not provide explanatory power regarding my hypothesis. However, through graphical analysis, I was able to identify specific patterns and draw a different conclusion. As seen below, while volume does not explain price, it has become possible to predict price volatility.
* Additionally, my data was more suited to unsupervised algorithms, which made the initial clustering challenging. However, by applying the k-means algorithm, I was able to obtain the graph shown above.
 [**The linear regression results**](linear.png)
 [**This is result of supervised learning algorithm**](supervised.png)
 [**This is the result of kmean cluster**](kmean_clust.png)
 
 
 ------
 # limitations and improvements that could be made.
* Despite using various algorithms such as Tree Classifier and Support Vector Machine (SVC), it has not been conclusively proven that trading volume affects price volatility. To overcome this, we plan to collect more data to identify variables that influence price.

* Our improvement strategies include:
    * Data Expansion: We intend to include more data to enhance the accuracy of our analysis.
    * Algorithm Diversification: We will explore the application of other machine learning algorithms.
* Through these two approaches, we expect to conduct more sophisticated analyses and clarify the relationship between trading volume and price volatility more distinctly.