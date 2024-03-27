# Project Name
House-Price-Prediction


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#Contact)

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house, and

- How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions
- The most important predictor variables are 'Neighborhood_Crawfor', 'GrLivArea', 'PropertyAge', 'MSZoning_FV','MSSubClass_160'.
- Lasso regression is best suited for the regularization purpose, and best possible alpha is 0.001.
- R2 is 0.91 for training data and 0.89 for test data.
- GrLivArea, GarageArea features have high positive correlation with the 'Saleprice'
- Ridge regression is best suited to address multicollinearity, and best possible alpha is 8.
- R2 is 0.91 for training data and 0.89 for test data.


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn
- SKLearn
- Statsmodels

## Acknowledgements
- This project was inspired by live session of upGrad on Advanced Linear Regression.
- UpGrad tutorials on Linear Regression on the learning platform


## Contact
Created by [@samik0701]