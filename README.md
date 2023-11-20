## Advertising_Budget_and_Sales
(I have taken the data from https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset).
#### The data focuses on how the Sales of a product(say) is influenced by Advertisements.
#### Our main goal is to identify which of the variable is more influencing the target variable and predict for future sales.
#### Based on the correlation of the data, it is clear that Sales is more influenced by TV Ad Budget and least influenced by Newspaper Ad Budget and there is lesser multicollinearity in the data.
#### From BoxPlot, we can identify the presence of outliers in Newspaper Ad Budget variable.
#### Since, only two outliers are present in the data, we choose to delete those rows containing the outliers.
#### Although linearity exists between Sales and TV Ad budget, We go for RandomForest algorithm. And the reason for it is that, LinearRegression is sensitive towards the outliers. As a result we use Random Forest(which uses DecisionTree). I have used SVR algorithm as well.
#### Based on R_square and Adjested R_square, we prefer RandomForest over SVR for this data.
