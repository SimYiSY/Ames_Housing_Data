# Ames Housing Data
Estates Agent are looking for the way to accurately predict saleprice of housing in Ames. By using data science to predict the prices, we will be able to come up with more competitive prices. We are also looking for features that homeowners can look into to potentially improve the property's sales value.
## Problem Statement

Create a regression model where we are able to see which features affect the price of property at sales in Iowa Ames

## Executive Summary

The data set that we will be exploring is the Ames Iowa Housing Dataset till the year 2010. In the Dataset there is a total of 81 features and 2051 columns. We will explore the data to see the correlation the features have to SalePrice, and also to build a regression model to predict the SalePrice of housing.

The final Kaggle models using Lasso, Ridge Regression uses 120 features to do the prediction with a RMSE score of around 28,000. At the end of the project, we will use the top 50 coefficient features to do our recommendations to homeowners and how they can improve their property prices using those features.

## Contents:
- [1. Importing of libraries](#1.-Importing-of-Libraries)
- [2. Importing Datasets](#2.-Importing-of-Datasets)
- [3. Manual Check of Dataset](#3.-Manual-Check-of-Dataset)
- [4. Data Cleaning](#4.-Data-Cleaning)
- [5. Exploratory Data Analysis(EDA)](#5.-Exploratory-Data-Analysis(EDA))
- [6. Pre-Processing](#6.-Pre-Processing)
- [7. Model_Benchmarks](#7.-Model-Benchmarks)
- [8. Model_Tuning](#8.-Model-Tuning)
- [9. Kaggle Submission](#9.-Kaggle-Submission)
- [10. Analysis & Recommendation](#10.-Analysis)


Links:
[Kaggle challenge link](https://www.kaggle.com/c/dsi-us-6-project-2-regression-challenge/data)

# Business Recommendations:

## Most valuable features
Location of the house matters, as most of the high coefficient features are Neighbourhood, condition and land contour of the property.

## Least valuable features
Generally having a less quality and older building will affect the property's value. 

## Features for homeowners to consider
Ames House buyers generally values luxury, quality and space of the houses
Certain features enhancement will improve saleprice: Heating, Fireplace, Garage, Baths
Having a good exterior of the house will fetch a higher price
The newer the house, the better the price

## Will the model generalize to other cities?
No, as the features that are used here are mostly related to Iowa and not other locations. Certain features might not be as relevant as compared to other places. 

## How to improve the model from here?
If possible, adding a few more features would be good for predicting the price of a property, as our findings has shown that location of the property matter most. features such as supermarkets, schools or malls that are near the property might be a few good features to consider collecting

As for modeling wise, we can consider using more intricate models like RandomForest or XGboost to get a more accurate score.