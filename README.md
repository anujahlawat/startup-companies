#### statsmodels|sklearn|matplotlib|pandas|numpy
#### ols|summary()

**Task :** build a multilinear regression model to predict profit

**Summary :** 
I build a multilinear regression model using : ols method
various steps for multilinear regression models are :
##### 1.EDA
+columns names
+columns data types
+duplicacy in records
+outlier detection
##### 2.checking linearity
+ pairplot
##### 3.correlation analysis
+ correlation (relation between x and y)
++ (point to notice - 1 : is there any relation between x and x) 
+ building model (trial mode)
++ (point to notice - 2 : rquared, AIC, p-value, adj_rsquared)
##### 5.dealing with problematic columns 
+ a-1) checking if x and x have good correlation
+ a-2) is p-value significant or not
+ multicollinearity (VIF) (checking how individual feature affecting the model prediction)
+ error / residue handing
+ improving model (trial mode)
##### 6.dealing with problematic rows
+ checking influential points (cook's distance)
+ improving model (trial mode)
After dealing with all the above case we build our final model. Final model has good R-squared value, less AIC value, significal p-value. Having all these requirements, we can now approve our model.

**Conclusion :**
models	Rsquared
0	model	0.961758
1	model1	0.961316
2	model2	0.961086
3	final_model	0.965359
