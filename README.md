HOUSE PRICE PREDICTION ASSIGNMENT-USING RIDGE AND LASSO REGRESSION
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 
The company is looking at prospective properties to buy to enter the market. we  are required to build a regression model using regularisation techniques like Ridge and Lasso in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
we need to find out two things which will help the company :
1.which variables are more efficient in predicting the price of a house.
2.how those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Methods used](#methods-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Analysis:A company from us wants to enter  Australian market.it is looking at essential properties to buy so that they can enter the market.
- Bussiness goal:we are required to build the model which will help the managment to understand how exactly the prices vary in variables.They can accordingly manipulate
the strategy of thr firm and concentrate on areas that will yield returns.helps in understanding pricing dynamics.
- Data:sales of houses in Australia-(train.csv)


## Methods Used
- Reading and understanding the Data: 1.importing neccesary libraries. 2.checking for Null values. 3.Dropping unnecessry columns. 4.visualizing numerical and      categorical variables. 5.using heatmap to check correlation between variables. 6.univariate analysis7.Bivariate 7.Explorartory data Analysis.
- Data Preparation: 1.creating dummy variables. 2.splitting into train and test data. 3.rescaling of variables using min-max scaler. 
- Training the Model: storing in y value  the target variables  and x except has target variable and all.
- Model Building and model Evaluation: 1. using Linear Regression 2.using Ridge Regression 3.Using Lasso Regression using the optimal lambda value 
- evaluating all the models on train and test data.


## Conclusions
- we used lasso model with help of metric values like r2 score of 0.8851
- used Lasso model indeed beacuse it helps in feature selection and takes coefficients towards 0.
- lambda value(optimal) for Ridge is - 1
- lambda value(optimal) for Lasso is -0.001
- Top predictors are:
1.MSZoning_RL- Identifies the general zoning classification of the sale.
2.RoofMatl_WdShngl- Roof material
3.Foundation_PConc- Type of foundation Poured Contrete	
4.Neighborhood_StoneBr- Physical locations within Ames city limits Stone Brook
5.HouseStyle_2Story- Style of dwelling


## Technologies Used
-pandas - version 1.4.2
-numpy - version 1.21.5
-seaborn - version 0.11.2
-matplotlib - version 3.5.1
-plotly - version 5.6.0
-statsmodels - version 0.14.0
-sklearn - version 1.0.2.
-scipy - version 1.7.3

## Acknowledgements
Greatful to UpGrad for giving an indeed chance to work on this project.


## Contact
Created by [@tejaswini1968] - feel free to contact me!


