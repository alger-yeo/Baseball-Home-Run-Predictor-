# Baseball Home Run Predictor

A machine learning project that predicts the number of home runs a player will hit based on historical data. Uses linear regression to model the relationship between various player statistics and home run counts. Evaluates performance using RMSE and compares against a naive baseline model.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Usage](#usage)
- [Modeling Approach](#modeling-approach)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Improvements](#future-improvements)

## Project Overview

This project explores different variables to predict home run counts like:
- **strikeouts**
- **throws**
- **base on balls**
- **height**
- **weight**


## Features

- Cleaned and preprocessed data
- Exploratory Data Analysis (EDA) to identify trends and patterns
- Trained linear regression model

## Data Source

- The dataset used was sourced from Baseball Databank, containing historical baseball.

## Technologies Used

- **Python**
- **Pandas** 
- **NumPy** 
- **SciPy** 
- **Matplotlib & Seaborn** 
- **Scikit-learn** 
- **feature-engine** 
- **Jupyter Notebook** 


## Usage

Download and open `Home_Run_Prediction_Model.ipynb` with Jupyter notebook to:

- Load and explore the dataset
- Train and test machine learning models
- Preprocess data
- View evaluation metrics and conclusions

## Modeling Approach

- **Preprocessing:** 
- **Train-Test Split:** 70/30 split for model evaluation
- **Model Compared:** Linear Regression and Naive Baseline

## Results

- The linear Regression Model's test data metrics outperformed the naivebaseline with MSE of 26.56, an RMSE of 5.15 and an R² of 0.60.

## Future Improvements

- Incorporating additional relevant features 
- Develop a front-end visualization dashboard

## License
- Baseball Databank is a compilation of historical baseball data in a convenient, tidy format, distributed under Open Data terms.
- This dataset is distributed under the [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/). 
- Most of the data is provided by the [Chadwick Baseball Bureau](http://www.chadwick-bureau.com).
- Based in part on the Lahman Baseball Database, version 2015-01-24.
- Copyright © 1996–2015 by Sean Lahman.
- Parks.csv and HomeGames.csv are derived from game logs and park codes published by [Retrosheet](http://www.retrosheet.org).
- All data is provided as-is and may not be updated regularly.
