# Investment Portfolio

![](InVestment-3.png)

## Breakdown
- Project Description
- Technical Dependencies
- Features
   - Data
   - Notebooks


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

### Features
The following are various peaces to build an investment portfolio by the highest growth predicted by implementing various models to company stock data of 2017 and 2018. By using the insights gleaned along with additional analysis to recommend a portfolio of 12 company investments that maximize the 12-month return of an overall \$1,000,000 investment.

#### Data
- **Company Fundamentals 2017.csv** 
- **Company Fundamentals 2018.csv** 
- **Data Dictionary** 



#### Notebooks

> **EDA.ipynb**  \
> The notebook focuses on exploring the provided datasets. It includes data manipulation, data segmentation, data visualizations, and correlation tests.       
> The notebook is helpfull to understand the provided stock price data and understand some of the features that affect the closing prices of the year.

> **Classification.ipynb**  \
> The notebook applies some simple machine learning models to the unedeted data with the main features being company number, quarter closing prices, opening price 
> and closing prices of the year 2017. The model used is Naive Bayes with 5-fold cross validation method to determine accuracy. 

> **Representation.ipynb**  \
> The notebook focuses on data preprocessing. We first calculate the principle components of our datapoints and conduct some correlation test between the 1st, 2nd 
> components and the growth of the stocks prices from start of the year til the end. The processed data is later stored in csv files to be used in later notebooks.

> **Regression.ipynb**  \
> The notebook uses our preprocessed data and the new dataframes built in the previous notebook to apply through a linear regression modelwith 5-fold cross-validation method to determine accuracy.

> **Tuning.ipynb**  \
> The notebook focuses on tuning our the models we have experimented with in the previous notebooks to achiave the best accuracy for the predictions of closing 
> stock prices.


