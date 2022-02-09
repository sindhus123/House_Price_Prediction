## House_Price_Prediction
Predicting the price of house using Advanced Regression and Regularisation
Problem Statement:
A US-based housing company has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.
The company is looking at prospective properties to buy to enter the market. 
You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Steps Followed
     1. The data is analaysed to understand the columns,rows and the values associated with it
     2. Unwanted columns which are not useful for analysis are identified and removed
     3. Missing values are checked and treated appropriately
     4. Outliers are checked and the replaced with the mean/ mode values as per the data
     5. Univariate and birvariate analysis are done
     6. The assosciation of target variable 'Salesprice'with other variables is analysed
     7. After data cleaning, train & test split made
     8. Scaling and trasformation done on the data
     9. Linear Regression model is built using RFE with R2 value of 0.86
     10. Ridge regression (alpha = 10) is developed and the r2 value is 0.892
     11. Lasso Regression (alpha = 0.001) is developed and the r2 value is 0.889
     12. The coefficents of the models are observed
     
## Summary
    1. R2 Values - Train ( Ridge - 0.892; Lasso - 0.889)
       R2 Values - Test  ( Ridge - 0.878; Lasso - 0.881)
    2. Significant variables affecting the sale price are 
        HouseStyle (2Story), Overall Quality (Good), Overall Condition, 1stFloor SF & Garage details
