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

Using Boston Airbnb Open Data from Sept 2016 to Sept 2017, the goal of this project is to answer three business questions: 

1. What is the cost variation for homestays in Boston?
2. How neighborhood and review scores rating relate with each other?
3. What are the rules, facilities and room type most offered?

The files related to this case, can be found in [Boston Airbnb Open Data in Kaggle](https://www.kaggle.com/airbnb/boston) which include: 

* Listings, including full descriptions and average review score
* Reviews, including unique id for each reviewer and detailed comments
* Calendar, including listing id and the price and availability for that day

## File Descriptions <a name="files"></a>

There is one notebook that was developed to answer the three questions using basic Exploratory Data Analysis. Calendar and Listings were the csv files condidered in this case. Moreover, Markdown cells were used to explain the steps considered to each business question.

## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@klever.mera/thinking-to-travel-to-boston-after-the-lockdown-f84a99ec728e).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Boston Airbnb Open Data in Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/boston).  Otherwise, feel free to use the code here as you would like! 

