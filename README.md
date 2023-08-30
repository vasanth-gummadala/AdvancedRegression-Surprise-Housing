# Advanced Regression - Suprise Housing Assignment

## Problem Statement

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
Which variables are significant in predicting the price of a house, and
How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

### Business Goal:
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.


## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Importing Libraries](#importing-all-the-libraries-and-enabling-common-settings)
3. [Common Functions](#common-functions)
4. [Data Understanding](#data-understanding)
    1. [Importing Data](#importing-data)
    2. [Data Info](#data-info)
5. [Data Cleaning](#data-cleaning)
    1. [Remove Empty Rows](#remove-empty-rows)
    2. [Remove Empty Columns](#remove-empty-columns)
    3. [Remove Unwanted Columns](#remove-columns-having-majority-values-as-nulls)
    4. [Data Conversion](#data-conversion)
    5. [Data Imputation](#data-imputation)
6. [Data Exploration](#data-exploration)
7. [Model Building](#model-building)
    1. [Ridge](#ridge-regression)
    2. [Lasso](#lasso)
8. [Model Comparison](#model-comparison)
9. [Inference](#inference)
10. [Subjective Questions](#subjective-questions)
    1. [Question 1](#question-1)
    2. [Question 2](#question-2)
    3. [Question 3](#question-3)
    4. [Question 4](#question-4)