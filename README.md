# Advertising_Budget_and_Sales
(I have taken the data from # https://www.kaggle.com/datasets/yasserh/advertising-sales-dataset).
#### This data focuses on how the Sales of a product(say) is influenced by Advertisements.
## Goals:
#### 1. To identify which of the variable is more influencing the target variable
#### 2. Predict for future sales.

## Analysis
#### 1. Based on the correlation of the data, it is clear that 'Sales ($)' is more influenced by 'TV Ad Budget ($)' and least influenced by 'Newspaper Ad Budget ($)' and there is lesser multicollinearity in the data.
#### 2. From BoxPlot, we can identify the presence of outliers in Newspaper Ad Budget variable.
#### Since, only two outliers are present in the data, we choose to delete those rows containing the outliers.

## Algorithms used:
#### 1. Random Forest (uses descission tree)
#### 2. SVM

### (Reason for not using Linear Regression is that it is sensitive towards the outliers)

## Accuracy of the model
### 1. R_square
#### a) Random Forest: 
#### train --> 99.7%
#### test --> 98%
#### b) SVM: 
#### train --> 75%
#### test --> 74.6%
### 2. Adjusted R_square
a) Random Forest: 
#### train --> 99.7%
#### test --> 97.6%
#### b) SVM:
#### train --> 70.3%
#### test --> 69.8%
### Thus, based on R_square and Adjested R_square, we choose Random Forest as it suits well for the given data.

