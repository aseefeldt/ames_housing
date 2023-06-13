# Predicting the Prices of Homes in Ames Iowa without Zillow 
## Overview 
Zillow has become a staple in the housing market.  Unfortunately with their overextension of their mortgage business, they are no longer in business.  Therefore, it is important to create a model that can predict the price of new homes coming onto the market.  Fortunately Ames has an Assessment Office that collects information on all homes.  
## Purpose 
The Purpose of this project is to use create a home prediction model that will replace Zillow.  This will allow our adgents to predict home price and thus better serve our clients.  
## Data Dictionary 
The data dictionary can be found here:  [data description](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt).
## Executive Summary
The dataset from the Ames Assessment Office consists of 82 columns of numerical and categorical data with real data and null.  First the data was cleaned by removing outliers in the Lot Area and Masonry Veneer.  Next the null values of Lot Frontage, Year Garage were built, and Masonry Veneer were replaced with the mean of their values.  Next the categorical columns were One Hot Encoded using the pandas dummies function.  This created several columns that were not in the test and train dataset, so those columns were removed from both datasets leaving 579 columns) 

A linear model was fit to these categories, and as expected the model was overfit.  Therefore the columns were ordered by correlation with the sale price and the values in the middle (closest to zero) were removed.  The R2 scores were reviewed and the combination that had the highest success was to keep the top 125 columns and the lowest 112 columns leaving 342 columns.  

A lasso model and ridge model were also fit. The best fit and score was given by the ridge model which is labeled ridge in this folder.  

It is recommended that we use the ridge model to predict home prices that are coming onto the market.  With this model we are able to predict a new home's price with greater accuracy than other methods.  By accurately predicting the sale price we will be able to better serve our clients, gauge future income, and negotiate for better prices. 
# ames_housing
# testing_project
# testing_project
