# Advanced_Regression - {Ridge & Lasso} <br>
## ***Ashwini Abhang***
#### Problem Statement<br>
*A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.*

*The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.*

*The company wants to know:<br>
Which variables are significant in predicting the price of a house, and<br>
How well those variables describe the price of a house.<br>
Also, determine the optimal value of lambda for ridge and lasso regression.*

### Business Goal 
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions
After creating model in both Ridge and Lasso we can see that the r2_scores are almost same for both of them but as lasso will penalize more on the dataset and can also help in feature elimination. I am going to consider that as my final model.
After compairing both the model we can see that the below Features are best explaining the DataSet.

`Best alpha value for Lasso : {'alpha': 0.001}`<br>
`Best alpha value for Ridge : {'alpha': 0.9}`

## Technologies Used
Jupyter Notebook

## Acknowledgements
- This project was inspired by IIIT Banglore

## Contact
Created by [@Ashu1905] - feel free to contact me!
