# [Project 1: Used Cars Price Prediction Using Multiple Regression: Project overview](https://leonardogiroldo.github.io/Leonardo_Portfolio/)
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
* I checked also the probability distribution function for the numerical variables and removed the top 1% of the observations from the variables ‘Price’, ‘Mileage’, ‘Engine’ and ‘Year’




