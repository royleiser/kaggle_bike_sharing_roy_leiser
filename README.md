# Kaggle's Bike Sharing Demand challenge
My attempt to solve Kaggle's 'Bike Submission Demand' competition as my final project for Naya's Data Science course by @Amit Rappel.

This code will achieve a score of 0.44813 according to Kaggle which as of today (2018-01-12) puts me in the 824 place.

# Summary

## 1. EDA
* Histogram the data
* Create feature correlation heatmap
* Test increase demand year-over-year, month-over-month

## 2. Feature Engineering / Data Manipulation
* Break Datetime into time measures: Year, Month, Day, Weekday, Hour
* Round fraction columns: Humidity, Windspeed, Temp, Atemp
* Remove outliers from Windspeed
* Apply Log(x+1) on the target column (Count)
* Scaling of numeric variables using various scalers

## 3. Execution
* Improve XGBoost model using gridserachCV

## 4. Validation
* RMSLE function (updated to match the log1p manipulation)
* Cross Validation

## 5. Ideas that didn't improve the model
* Create dummy variables for hours
* Seperate data to casual and registered (single column target)
* Bin hours into parts of day
* Remove outliers from Humidity

## 6. Preparing competition submition 
