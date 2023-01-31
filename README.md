# House Price Prediction - Advanced Regression Analysis

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## Problem statement
The company wants to know:
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house.

## Technologies Used
- Python 
- Pandas, Numpy, Seaborn
- Statsmodel, Scikit Learn, GridSearchCV
- Process: Exploratory data analysis, data cleaning, data transformation, model building, hyperparameter tuning

## Conclusions

- Neighborhoods such as NoRidge, NridgeHt, StoneBr tend to have higher sale price while IDOTRR, MeadowV and BrDale have lower sale price.
- Suprisingly, number of bedrooms above ground did not seem to affect sale price
- After performing regression analysis, top 5 features that are highly correlated with sale price are 1st and 2nd Floor square feet, Overall quality, year built and total basement square feet. Other significant features that help to determine sale price are Lot area, garage area, and full bath. 

## Acknowledgements
- This project was a part of Advanced Linear Regression Assignment by Bangalore IIITB and Liverpool John Morris University

## Contact
Created by [Chirag Navadia](https://www.linkedin.com/in/cnavadia/) - feel free to contact me!

