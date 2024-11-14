# Predicting House Prices for a real estate store (with Python)
See the notebook of this project [here](Regression_house_prices_tehran.ipynb)

## 1. Description

In this project, I performed a supervised learning clustering task using several algorithms of regression, what allowed us to obtain a good model that predicts the Price of a house based in its features. I considered a dataset of house prices in Tehran that is available publically at Kaggle, but the techniques can be applied to predict prices in any other city.

First, I did an Exploratory Data Analysis of the prices according to the following characteristics of the house: Area, number of Rooms, Address, if it has ou nor Parking, Elevator, Warehouse. This gave insights about what features influentiate the Price to be greater or smaller. After I used the several Machine Learning algorithms for Regression (Simple and Multiple Linear regression with OLS, Lasso Regression, Ridge Regression, Decision Tree, Random Forest, Gradient Boosting, LGBM, XGBoost and CatBoost) to predict the price of the houses. I adjusted the hyper-parameters using GrisearchSV and RandomSearchSV to improve the performances of the models. 

## 2. Tools

The tools used were Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn), Jupyter Notebook, and Github (version control). We used Statistics for Exploratory Data Analysis (EDA) and Machine Learning algorithms.

## 3. Business problem and project objectives

**Problem statement:**

A real estate store wants to understand what characteristics of the house influence its price and wants to develop a Model to predict the price of houses in a city based on their characteristics.

For this, they have a dataset with information of almost 4000 houses in their city. So, the project objectives are:

+ Make an Exploratory Data Analysis of the house prices;
+ Develop models to predict the price.

## 4. Solution

The steps for the solution were:

1. Introduction.
2. Definition of the Business Problem.
3. Data Cleaning.
4. Exploratory Data Analysis
5. Feature Engineering.
6. Machine Learning Models of Regression
7. Tuning hyper-parameters.
8. Comparing the performances of the models.
9. Conclusion.

## 5. Result

The Exploratory Data Analysis above shows that the Price tends to be greater when the Area is greater, when there are more Rooms and when there are Parking, Warehouse and Elevator. It makes very sense when we think about these possibilities, but the features that are more related are Area and the number of Rooms.

We implemented several Machine Learning models, the best performance was obtained for Random Forest after tuning the hyper-parameters. We summarize the performances in the following pictures:

[Root Mean Squared Error of the different models](img/rmse.jpg) [R-squared (R2) of the different models](img/r2.jpg)

Visualization of Predicted x Real Prices:

[Predicted Price x Real Price](img/predicted_x_realprice.jpg)

## 6. Source (dataset link)

The dataset was collected from Kaggle and is public.

Link:  https://www.kaggle.com/datasets/valakhorasani/tehran-house-prices-dataset

## 7. Contact me

+ Linkedin: https://www.linkedin.com/in/ricardo-bortolotti/

+ Github: https://github.com/ricardo-bortolotti

+ Gmail: ricardo.t.bortolotti@gmail.com
