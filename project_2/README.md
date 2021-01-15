# Project 2 - Ames Housing Data and Kaggle Challenge

## Problem Statement

Property business is a high value and productive business; and for most people, it will be the biggest financial decision of their lives. In this project we aim to create and iteratively refine a regression model to predict the price of a house based on its features.

Getting a reliable and accurate prediction of the sale price of a house is extremely useful for both sellers and buyers, as it gives them a benchmark of how much a certain property should cost, given the features it has. This can help to prevent over or under selling, and can help both prospective owners and sellers reach their goals more effectively.

We also hope to better understand which features of a property will potentially increase the sale price of a house, as well as what features may hurt the prospects of a house sale. This information is extremely valuable to prospective sellers, as they will then be able to carry out targeted improvements to their home before trying to sell it.

## Executive Summary

This project is carried out in 5 main steps:

**1. Data Cleaning**

This includes changing datatypes to the appropriate ones, handling missing data and checking for outliers.


**2. Exploratory Data Analysis and Feature Engineering**

Here we explore each feature, and study their correlations to each other as well as to the target variable (Sale Price). We also study their distributions. Depending on the analysis, we may drop certain features, or we may also create interaction terms between correlated features.


**3. Data Modelling and Predictions**

We first create a baseline model that will carry out predictions before any feature engineering is done. This will allow us to iteratively improve our feature engineering process, as we will be able to see if any feature engineering will improve our predictions or potentially make it less accurate.


**4. Evaluation of Model**

We use relevant metrics to evaluate our model and predictions, and we also interpret the results of our data analysis and modelling


**5. Conclusions and Recommendations**

Based on our data analysis, we provide recommendations that will be useful to both property seller and buyers.

## Notebooks and Datasets

There are two datasets provided by Kaggle. They can be found in the datasets folder, and are titled 'train.csv' and 'test.csv'. From these two datasets, we then generate four more: train_baseline.csv, test_baseline.csv, Train_Cleaned.csv and Test_Cleaned.csv. The baseline datasets only undergo data cleaning but **no** feature engineering. The cleaned datasets are produced from extensive exploratory data analysis and feature engineering.

There are four notebooks that show the entire data process:

1. Data Cleaning and EDA (Train)
2. Data Cleaning (Test Data)
3. Modelling (Train Data)
4. Modelling (Baseline)

The notebooks are annotated with comments and markdown cells for interpretation and explanations.

## Conclusions and Recommendations

#### Top 10 Qualities

From our modelling process, we have found that the **features which will be the best predictors for a higher sale price are**:

1. Living area above ground (including 1st and 2nd floor area)
2. Overall material and finish of the house, as well as overall condition and functionality
3. Basement area, how much of it is finished properly, and exposure
4. Contour of land and lot area
5. Age of Garage and how many cars it can fit
6. Exterior quality, Masonry veneer area
7. Kitchen quality
8. Number of full baths in Basement
9. Screen Porch area
10. Number of fireplaces


These might seem straightforward, but the data does show the importance of these features. Depending on whether you are a buyer or seller, these are the top significant features to look out for.  


#### Neighborhoods

It is well known that houses in certain locations will be able to command higher sale prices. While some aras are fairly obvious to predict, for most other locations it can be quite difficult as this is a subjective feature and different people may have different ideas. However, our data shows clearly that the neighborhoods that are preferred by buyers are:

1. Northridge Heights
2. Stone Brook
3. Northridge
4. Crawford


There are a few neighborhoods which buyers seem to less keen on, namely:

1. North Ames
2. Old Town
3. Edwards
4. College Creek
