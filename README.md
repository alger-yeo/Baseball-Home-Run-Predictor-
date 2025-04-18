# Baseball Home Run Predictor

A machine learning project that predicts the number of home runs a player will hit based on historical data. Uses linear regression to model the relationship between various player statistics and home run counts. Evaluates performance using RMSE and compares against a naive baseline model.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Data Source](#data-source)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling Approach](#modeling-approach)
- [Evaluation Metrics](#evaluation-metrics)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)
- [Acknowledgements](#acknowledgements)

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

- The dataset used was sourced from MLB Statcast, containing hit-by-hit data from professional baseball games.
- Key variables include:
  - `launch_angle`
  - `launch_speed` (exit velocity)
  - `hit_distance`
  - `hang_time`
  - `is_home_run` (target label)

## Technologies Used

- **Python**
- **Pandas** – data manipulation
- **NumPy** – numerical computation
- **SciPy** - statistic
- **Matplotlib & Seaborn** – data visualization
- **Scikit-learn** – model building and evaluation
- **feature-engine** - feature engineering
- **Jupyter Notebook** – code development and documentation

## ⚙️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/alger-yeo/Baseball-Home-Run-Predictor-.git
   cd Baseball-Home-Run-Predictor-
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

Open the `Home_Run_Prediction_Model.ipynb` notebook to:

- Load and explore the dataset
- Train and test machine learning models
- Preprocess data (feature scaling, missing value handling)
- View evaluation metrics and conclusions

## Modeling Approach

- **Preprocessing:** StandardScaler used to normalize features.
- **Train-Test Split:** 70/30 split for model evaluation.
- **Model Compared:** Logistic Regression and Naive Baseline

## Results

- The linear Regression Model's test data metrics outperformed the naivebaseline with MSE of 26.56, an RMSE of 5.15 and an R² of 0.60.

## Future Improvements

- Incorporating additional relevant features 
- Develop a front-end visualization dashboard
