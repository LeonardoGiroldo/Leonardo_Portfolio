# [Project: Used Cars Price Prediction Using Multiple Regression: Project overview](https://leonardogiroldo.github.io/Price_Prediction/)
* In this project, I learned how to create a Multiple Regression model to predict used cars prices
* The data used was available in the 365 Data Science Complete Program 

# Code and resources used:
Python Version: 3.7
Packages: pandas, numpy, matplotlib, sklearn, Seaborn
365 Data Science Complete Program course: https://365datascience.com/courses/

# Data Collection
The dataset used was historical car used prices along with information about brand, mileage, engine, year and model and was available in the 365 Data Science Complete Program course

# Data Cleaning:
* After importing the data to a Jupiter notebook, I checked for missing and null values and explored the descriptive statistics of the variable and decide to drop the ‘Model’ variable as it had 312 different models and a lot of the information from ‘Model’ could be engineered from the variables ‘Brand’, ‘Year’ and ‘Engine’
* I removed the missing values as they represented less than 5% of the observations
* I checked also the probability distribution function for the numerical variables and removed the top 1% of the observations from the variables ‘Price’, ‘Mileage’, ‘Engine’ and ‘Year’ in order to remove outliers

![](https://github.com/LeonardoGiroldo/Leonardo_Portfolio/blob/main/Image1-project1.png)

# Exploratory Data Analysis (EDA)
When exploring the data, I checked for the OLS assumptions and as the patterns of the variables were not linear, I performed a log transformation in the ‘Price’ variable as its distribution was exponential.

![](https://github.com/LeonardoGiroldo/Price_Prediction/blob/main/Image2-project1.png)

I also checked for multicollinearity through VIF (Variance inflation factor) and dropped the variable ‘Year’ as its VIF was almost 10.
I also created dummy variables for the categorical variables.

# Model Building
* Declared the dependent (Target) and independent (inputs) variables
*	Scaled the data by using the StandardScaler from SKlearn
*	Split the data with a test size of 20% using train_test_split 
*	Created the Regression Model






