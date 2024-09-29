# House Price Prediction Using Advanced Regression
> Build a regularized regression model to understand the most important variables to predict housing prices in a US market
---

## Table of Contents
* [General Information](#general-information)
* [Solution Approach](#solution-approach)
* [Python Libraries Used](#python-libraries-used)
* [Contributor](#contributor)

## General Information
### Problem statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.
 
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

### Business goal
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company wants to know:
- Which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house.

## Solution Approach
- **Step 1. Data Understanding, Preparation and EDA**
	- Duplicate Rows Detection
	- Missing Value Handling
	- Outlier Treatment
	- Visualizing & Analyzing Numerical Features
		- Data Visualization of Numerical Continuous Features
		- Data Visualization of Numerical Discrete Features
		- Correlations Heatmap among numerical variables
		- Dropping Less Significant Features
	- Visualizing & Analyzing Categorical Features
		- Data Visualization of Categorical Features
		- Data Preparation
			- Label Encoding for Ordered Categorical Features
			- One-Hot Encoding for Unordered Categorical Features
     	- Features Correlating with Target Variable
        
- **Step 2. Model Building, Tuning and Evaluation**
	- Transformation of Target Variable
	- Train - Test Split
	- Feature Scaling
	- Linear Regression
		- Primary Feature Selection using RFE
		- Residual Analysis
		- Model Evaluation
	- Ridge Regression
	- Lasso Regression
	- Model Evaluation Comparison - Linear vs Ridge vs Lasso
   	- Choosing the final model and most significant features

      
## Python Libraries Used
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborne - version 0.12.2
- Scikit-learn - version 1.2.2
- Statsmodels - version 0.14.0


## Contributor
Created by [@Anupam Maiti](https://github.com/dynamicanupam) - feel free to contact me!
