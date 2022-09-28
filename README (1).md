# Surprise House Sale Prediction
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.

The company is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Required to model the price of houses with the available independent variables and This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The optimal lambda value in case of Ridge and Lasso is as below:
Ridge - 1.0
Lasso - 0.0001

The Mean Squared error in case of Ridge and Lasso are:
Ridge - 0.017569
Lasso - 0.017136
The Mean Squared Error of Lasso is slightly lower than that of Ridge.

- Since Lasso helps in feature reduction (as the coefficient value of one of the lasso's feature to be shrunk toward 0) and helps to increase model interpretation by taking the magnitude of the coefficients, Lasso has a better edge over Ridge.

Hence based on Lasso, the factors that generally affect the SalePrice are:
MSZoning_FV
1stFlrSF True
Foundation_Stone
MSZoning_RH
GarageType_BuiltIn
MSZoning_RL
GarageType_Attchd
OverallQual
MSZoning_RM
Foundation_PConc

- Therefore, the variables predicted by Lasso in the above mentioned are the significant variables for predicting the price of a house and it is recomended to give these variables utmost importance while planning to achieve maximum SalePrice.
- 
- From R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 91% variation of SalePrice. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Lasso Regression
- Ridge Regression


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->






<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
