# Airbnb Price Forecasting
Ensemble Model Framework for Airbnb Rental Price Forecasting

Notes for Krishna:


1) LassoCV is taking too long to run, it might be due to multicollinearity


2) XGBoost feature selection not working at the moment due to negative R2 values produced by the models
(This may be because I am using only 10% of the data). But I still want to run, so that i could include the observations in the report
Mutual Information: Mutual information does not work well wehn we use highly correlated data. Our data is correlated

3) Feature selection, I think we can go with PCA, but the code needs to be updated for Linear Regression, XGBoost and  


4) Outliers:
Right now I am using the same data for tuning and testing.
Need to decide what to do with the outliers
Code for tuning the parameters for isolation forest included, but need to run it. 

5) I need to run the code for the meta model, haven't gotten a chance to test it yet.



