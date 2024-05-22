# House Pricing 
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

The company wants to know:
- Which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house

The project contain a jupiter notebook which reads a csv file which contains data of house prices and based on that creates a linear model, Ridge and Lasso model to find the variables that impact the price of house.


## Conclusions

- The Linear regression model(RFE) has worst train and test R2 scores
- For the linear regression model(RFE) difference between train and test score is high so model might be overfitting the training data.
- Ridge and Lasso have similar train score but Lasso has more drop in test score as compared to Ridge.
- Since the number of features are high we will choose Lasso regression model

 Which variables are significant in predicting the price of a house. 
- Living areas in square feet
- Excellent overall quality
- Excellent overall condition
- Total square feet of basement
- Very Good overall quality

## Technologies Used
- seaborn -Version: 0.13.2
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- scikit-learn - version 1.2.2
- statsmodels - version 0.14.0


## Contact
Created by [@githubusername] - feel free to contact me!
