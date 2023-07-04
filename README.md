# Advertising_Budget_and_Sales
The data focuses on how the Sales of a product(say) is influenced by Avertisements.
Our main goal is to identify which of the variable is more influencing the target variable and predict for future sales.
Based on the correlation of the data it is clear that Sales is more influenced by TV Ad Budget and least influenced by Newspaper Ad Budget.
From BoxPlot, we can identify the presence of outliers in Newspaper Ad Budget variable.
Though linearity exists between Sales and TV Ad budget, We go for RandomForest algorithm. And the reason for it is that, LinearRegression is sensitive towards the outliers. Whereas, RandomForest(which uses DecisionTree) is not sensitive towards the outliers.
Based on R_square, Adjested R_square and MeanAbsoluteError, we say that the model performs well for new data.
