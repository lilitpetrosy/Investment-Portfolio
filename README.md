# Investment-Portfolio

![](banner_project.jpg)

## Overview
The following are various processes to build an investment portfolio by the highest growth predicted by implementing various models to company stock data of 2017 and 2018. By using the insights gleaned along with additional analysis to recommend a portfolio of 12 company investments that maximize the 12-month return of an overall \$1,000,000 investment.

## Data Dictionary
The project includes a data dictionary that contains all the needed definitions and information for our 2017 and 2018 stock data features.

## Company Fundamentals 2017/2018.csv
The following are the two datasets that will be used to build the investment portfolio. 

## Notebooks
The various notebooks ordered in consecutive order conduct Exploratory Data Analysis that later will allow implementing various models like Bayesian, Regression, and k-fold cross-validation to build our investment portfolio.

> **Representaqtion.ipynb**  \
> This is the process of cleaning the data to have a more defind dataset, and have more accuracy in our predictions. We remove all variables that have more than    > 20% missing data, for the remainning missing data, we use the method of imputating data by butting the mean of the numeric variables for the missing numeric .    > values, and the median for the character values. To apply PCA methods, we filter the numeric values. PCA helps us normalize the data, to avoid having large scale > data. By visualizing the varience of each principal variable, we are able to see the variables with varying values. By later comparing PC2 and PC2 using a scatter > plot, it hels us see their relation to the growth variable, as we were able to see that PC1 and PC2 fit with the values of big_growth.
