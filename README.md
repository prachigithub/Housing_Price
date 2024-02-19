# Project Name
> Surprise Housing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

 

The company wants to know:

Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.
Also, determine the optimal value of lambda for ridge and lasso regression.

Business Goal 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary withthe variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

Downloads
Please find the dataset link [here] train.csv

## Technologies Used
- python 3.11.4
- jupyter notebook
- pandas 1.5.3
- numpy 1.24.3
- matplotlib 3.7.1
- seaborn 0.12.2
- statsmodels 0.14.0
- sklearn 1.3.0

## Conclusions
- Lasso is the best performing model with hyperparameter as .0001, while Ridge model has best hyperparameter as 2.0
- R2 Score for Lasso and Ridge is R2_score Test	0.885180(Lasso)	0.878812(Ridge)
- The various top five independent variables that impact the SalesPrice in Lasso Model.

independentVariable and betas respectively GrLivArea - 0.308287, OverallQual - 0.162438, OverallCond	- 0.094896, GarageCars	- 0.078638, MSZoning_RL	- 0.056504	

- The various top five independent variables that impact the SalesPrice in Ridge Model.

independentVariable and betas respectively OverallQual - 0.128202, GrLivArea - 0.095476, 1stFlrSF - 0.083750, OverallCond - 0.079901, 2ndFlrSF - 0.063707	
																																		

## Contact
Created by [prachigithub](https://github.com/prachigithub/) - feel free to contact me!