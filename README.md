# Covid--19-Prediction
# COVID-19 Prediction Project

## Overview

This project focuses on predicting the spread of COVID-19, specifically the number of deaths, using time series forecasting techniques. The prediction is done for a specific country, and machine learning models are employed for this purpose.

## Dataset

The dataset used for this project contains information about confirmed cases and deaths globally. The data is organized by country and includes daily updates.

- **File 1:** RAW_global_confirmed_cases.csv
- **File 2:** RAW_global_deaths.csv

## Project Structure

- **Data Preprocessing:**
  - Loading and cleaning the dataset
  - Handling missing values
  
- **Exploratory Data Analysis (EDA):**
  - Visualizing the data to understand trends and patterns
  - Checking for stationarity

- **Machine Learning Models:**
  - Implementing ARIMA for time series forecasting
  - Utilizing LSTM RNN for predicting cases and deaths for the next 10 days

- **Hyperparameter Tuning:**
  - Using GridSearchCV to find optimal hyperparameters for the models

- **Results and Visualization:**
  - Plotting predictions over time
  - Comparing actual vs predicted values
  
- **Documentation:**
  - README file to provide an overview of the project
  - Code comments for clarity
  - Jupyter notebooks for step-by-step execution

## Requirements

- Python 3.x
- Libraries: pandas, numpy, matplotlib, statsmodels, tensorflow (for LSTM)

## Instructions

1. Clone the repository:

```bash
git clone https://github.com/l-ordkp/COVID-19-Prediction.git
cd COVID-19-Prediction
