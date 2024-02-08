# Assignment-1-Linear-Regression

Welcome to your first practice lab! In this lab, you will implement linear regression with one variable to predict profits for a restaurant franchise.

1 - Packages
First, let's run the cell below to import all the packages that you will need during this assignment.
numpy is the fundamental package for working with matrices in Python.
matplotlib is a famous library to plot graphs in Python.
utils.py contains helper functions for this assignment. You do not need to modify code in this file.
2 - Linear regression with one variable

2.1 Problem Statement
Suppose you are the CEO of a restaurant franchise and are considering different cities for opening a new outlet.
You would like to expand your business to cities that may give your restaurant higher profits.
The chain already has restaurants in various cities and you have data for profits and populations from the cities.
You also have data on cities that are candidates for a new restaurant.

2.2 Dataset
You will start by loading the dataset for this task.
The load_data() function shown below loads the data into variables x_train and y_train.
x_train is the population of a city.
y_train is the profit of a restaurant in that city. A negative value for profit indicates a loss.
Both X_train and y_train are numpy arrays.

In this practice lab, you will fit the linear regression parameters $(w,b)$ to your dataset.
The model function for linear regression, which is a function that maps from x (city population) to y (your restaurant's monthly profit for that city) is represented as $f_{w,b}(x) = wx + b$.

GitHub: https://github.com/sarthakLU/Assignment-1-Linear-Regression
Medium: https://medium.com/@sjadav_53251/assignment-1-4bfab1dd7b1f
