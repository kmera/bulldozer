### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The libaries needed to run the code, using Python version 3.* are:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* scikit-learn
  * train_test_split
  * RandomForestRegressor
  * mean_squared_log_error, mean_absolute_error, r2_score
  * import RandomizedSearchCV

## Project Motivation<a name="motivation"></a>

As part of my journey in the field of Data Science, I chose [Blue Book for Bulldozers](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/description) for prediction using Machine Learning.

The goal of this project is to predict the sale price of a particular piece of heavy equiment at auction based on it's usage, equipment type, and configuaration.  The data is sourced from auction result postings and includes information on usage and equipment configurations.

The data for this competition is split into three parts, and can be found [here](https://www.kaggle.com/c/bluebook-for-bulldozers/data):

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

## File Descriptions <a name="files"></a>

There is one notebook that was developed to predict the sale price using Random Forest and Hyperparameter tuning with RandomizedSearchCV. Besides, Markdown cells were used to explain the steps considered not only for prediction but also for EDA.

## Results<a name="results"></a>

First, an EDA was done in order to get familiar with the datasets. Next, some process such as cleaning and feature engineering were needed to handle missing values (categorical and numerical). For modeling, Random Forests was considered to predict the price and also to improve the scores Hyperparameter tuning was also needed. Finally, the RMSLE (root mean squared log error) was determined as a score based on the evaluation requested in Kaggle, and a csv file which contains two columns: `SalesID` and `SalePrice` (test_predictions.csv) was generated and included in this repo.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Blue Book for Bulldozers in Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/c/bluebook-for-bulldozers/overview/description). Otherwise, feel free to use the code here as you would like! 

