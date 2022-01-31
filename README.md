# Udacity-Data-Scientist-Nanodegree-Assignment-1

The goal of this repository is to analyse a dataset using CRISP-DM methodology. The dataset used here is Seattle AirBnB data taken from kaggle. 

    In the notebook, we investigate a few questions using the data: are some neighborhood listings more expensive than others, are certain times of the year more expensive to visit Seattle, which are the important features related to the price of a property at any given point in time. 
    
    Directory Layout

    ├── Seattle AirBnB Data Analysis.ipynb  # Main Analysis File
    ├── calender.csv                    # Data
    ├── listings.csv                    # Data
    ├── reviews.csv                     # Data
    └── README.md
    
    Libraries Used
    1. numpy
    2. pandas
    3. matplotlib
    4. seaborn 
    5. sklearn (RandomForestRegressor, LinearRegression, Lasso)
    
    We wrangle the data a bit to get the relevant features from calender.csv and listings.csv and build some linear models and a Random Forest model. 
    
    Random Forest model did a good job of predicting the prices for the listings in the dataset. 
    
    A blog post describing the process and high level analysis is at: https://nirzaree.wordpress.com/2022/01/28/analysing-seattle-airbnb-data/
    
    Acknowledgements:
    1. [Udacity DataScientist Nanodegree Program](https://classroom.udacity.com/nanodegrees/nd025/)
    2. [Kaggle](https://www.kaggle.com/airbnb/seattle)
