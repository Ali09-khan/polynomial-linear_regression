# Predicting CPU Utilization

## Overview
This project focuses on predicting CPU utilization using polynomial regression models. The notebook evaluates models of varying polynomial degrees to determine the best-performing one.

## Features
- **Data Preparation:** Prepares time-series data using a sliding window approach.
- **Modeling:** Trains polynomial regression models on CPU utilization data.
- **Evaluation Metrics:**
  - **Root Mean Square Error (RMSE)**
  - **R² Score**

## Results
- **Best Model:** Polynomial regression of degree 2.
  - **RMSE:** 1.8477
  - **R² Score:** 0.9899

## Dependencies
- Python 3.x
- Libraries:
  - `numpy`
  - `matplotlib`
  - `sklearn` (for regression and evaluation)

## Usage
1. Load the data and preprocess it using the sliding window technique.
2. Train polynomial regression models with varying degrees.
3. Evaluate model performance on the test set using RMSE and R².
4. Use the best-performing model for predictions.

## Conclusion
The polynomial regression model with degree 2 demonstrated the best performance in predicting CPU utilization, offering both low RMSE and high R² values.

