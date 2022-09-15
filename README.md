#### statsmodels|sklearn|matplotlib|pandas|numpy
#### ols|summary()

**Task :** build a multilinear regression model to predict profit

**Summary :** 
I build a multilinear regression model using : ols method
various steps for multilinear regression models are :

##### 3.checking linearity
+ pairplot
##### 4.correlation analysis
+ correlation (relation between x and y)
++ (point to notice - 1 : is there any relation between x and x) 
+ building model (trial mode)
++ (point to notice - 2 : rquared, AIC, p-value, adj_rsquared)
    
### 5.dealing with problematic columns 
    + a-1) checking if x and x have good correlation then can we drop one of them
      a-2) is p-value significant or not
           (checking how individual feature affecting the model prediction)
    + multicollinearity (VIF)
    + error / residue handing
    + improving model (trial mode)
    
### 6.dealing with problematic rows
    + checking influential points (cook's distance)
    + improving model (trial mode)
I used ols to understand some basic terms like R-squared, adj. R-squared,  AIC, significance of p-value. 
It is obvious our first task is to prepare data ready for model building. In the initial step I check for data types of columns, null value detection, outlier detection etc.
In second step we check correlation between dependent and independent variables, if correlation is good then we build our first model and check for different values - R-squared, AIC, p-values.
further out task is to find problematic columns and rows and if any remove these and we further build new improved model.


**Conclusion :**
+ Model build using ols has R-squared = 95% which is good and LinearRegression have accuracy approximately in the line of 90's.
+ All the three techniues - LeaveOneOut, Kfold, train_test_split give approximately same accuracy except LeaveOneOut (60%) and this might be due to very small dataset I choose to build model.
