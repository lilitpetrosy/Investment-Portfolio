# Investment Portfolio

![](InVestment-3.png)

## Breakdown
- Project Description
- Technical Dependencies
- Features
   - Notebooks
   - Data
- Benefits and Uses
- Additional Reading Material


### Project Description
One of many ways investors determine their yearly investment portfolio is by multiple observations of past stock performances, current market trends, company news, and many other features that are relevant to the changes in stock prices. 
With more than 41000 publicly traded company stocks out in the market data science and machine learning allow us to consider a larger number of features and companies when determining best investment practices.

This project consists of various notebooks conducting exploratory data analysis to determine features that affect stock prices based on 2017 stock market data and later use different machine learning algorithms to predict stocks that will perform best in 2018. 

### Technical Dependencies
- [dplyr](https://dplyr.tidyverse.org)
- [ggplot2](https://ggplot2.tidyverse.org)
- [knitr](https://yihui.org/knitr/)
- [dt](https://rstudio.github.io/DT/)
- [mlr](https://mlr.mlr-org.com)
- [stringR](https://stringr.tidyverse.org)
- [randomForest](https://www.rdocumentation.org/packages/randomForest/versions/4.6-14/topics/randomForest)
- [knn](https://www.rdocumentation.org/packages/randomForest/versions/4.6-14/topics/randomForest)
- [svm](https://cran.r-project.org/web/packages/e1071/vignettes/svmdoc.pdf)
- [kfold](https://www.rdocumentation.org/packages/dismo/versions/1.3-3/topics/kfold)
- [PCA](https://towardsdatascience.com/principal-component-analysis-pca-101-using-r-361f4c53a9ff)
- [Naive Bayes](https://www.r-bloggers.com/2021/04/naive-bayes-classification-in-r/)

## Overview
The following are various processes to build an investment portfolio by the highest growth predicted by implementing various models to company stock data of 2017 and 2018. By using the insights gleaned along with additional analysis to recommend a portfolio of 12 company investments that maximize the 12-month return of an overall \$1,000,000 investment.

## Data Dictionary
The project includes a data dictionary that contains all the needed definitions and information for our 2017 and 2018 stock data features.

## Company Fundamentals 2017/2018.csv
The following are the two datasets that will be used to build the investment portfolio. 

## Notebooks
The various notebooks ordered in consecutive order conduct Exploratory Data Analysis that later will allow implementing various models like Bayesian, Regression, and k-fold cross-validation to build our investment portfolio.

> **Representaqtion.ipynb**  \
> The notebook focuses on Principal Component Analysis of our financial dataset. This helps us define the data in less dimensions without information loss.         > We create the new variables and store in a dataset to be used for further analysis.



### Investment Portfolio

- Describe very briefly but clearly what the project does.
- State if it is out-of-the-box user-friendly, so it’s clear to the user.
- List its most useful/innovative/noteworthy features.
- State its goals/what problem(s) it solves.
- Note and briefly describe any key concepts (technical, philosophical, or both) important to the user’s understanding.
- Link to any supplementary blog posts or project main pages.
- Note its development status.
- Include badges.
- If possible, include screenshots and demo videos.


### Core Technical Concepts/Inspiration

- Why does it exist?
- Frame your project for the potential user. 
- Compare/contrast your project with other, similar projects so the user knows how it is different from those projects.
- Highlight the technical concepts that your project demonstrates or supports. Keep it very brief.
- Keep it useful.


### Getting Started/Requirements/Prerequisites/Dependencies
Include any essential instructions for:
- Getting it
- Installing It
- Configuring It
- Running it
