# Surprise Housing - Advanced Regression <br>
`House Price Prediction using Ridge & Lasso regression model`
# _Ashwini Abhang (IIIT BANGLORE_2022)_
## Problem Statement<br>
*A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.*

*The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.*

*The company wants to know:<br>
Which variables are significant in predicting the price of a house, and<br>
How well those variables describe the price of a house.<br>
Also, determine the optimal value of lambda for ridge and lasso regression.*

## Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusion
### `Observation` <br>
Though the model performance by Ridge Regression was better in terms of r2 values of Train and Test,<br>
It is better to use Lasso Regression Model, since it brings and assigns a zero value to insignificant features, enabling us to choose better predictive variables.
It is always advisable to use simple yet robust model.<br> 

These are the final features that should be selected for predicting the price of house<br>
`Equation:` <br> 
Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10)+ 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients) <br>
 
### `INFERENCE` <br>
Suggestion for 'Surprise Housing' is used to keep a check on these predictors that are affecting the price of the houses.<br>
*`The higher values of positive coeficients suggests a high sale value.`* <br>
*`The higher values of negative coeficients suggests a decrease in sale value.`* <br>

`"We can conclude on this by saying that when the market value of the property is lower than the Predicted Sale Price, it is better time to buy these houses."`

## Technologies Used
Jupyter Notebook

## Acknowledgements
- This project was inspired by IIIT Banglore

## Contact
Created by [@Ashu1905] - feel free to contact me!
