# OIBSIP-TASK-2-Unemployment-Analysis-with-Python

This project analyzes unemployment trends in India during the COVID-19 pandemic using real datasets. It cleans and visualizes unemployment data, extracts insights such as peak unemployment periods, and provides a simple machine learning model to predict future unemployment rates.


## Project Overview

* Goal: Understand how unemployment rates changed during COVID-19 and forecast near-term trends.
* Datasets Used:

  * Unemployment in India.csv
  * Unemployment\_Rate\_upto\_11\_2020.csv
* Key Steps:

  1. Load and clean datasets (standardize column names, fix dates).
  2. Visualize unemployment rate trends with line plots.
  3. Identify peak unemployment periods during the pandemic.
  4. Train a simple Linear Regression model to predict unemployment for upcoming months.
  5. Save processed data, results, and predictions for future use.

## Tech Stack

* Python 3.11
* Libraries:

  * `pandas` for data cleaning and manipulation
  * `matplotlib` for visualization
  * `numpy` for numerical operations
  * `scikit-learn` for machine learning (Linear Regression)

## Features

* Cleans messy column names and fixes date formats automatically.
* Plots unemployment rate trends from multiple datasets on the same graph.
* Highlights peak unemployment values.
* Predicts unemployment rate for the next three months using a regression model.
* Exports:

  * Cleaned datasets
  * Summary statistics
  * Prediction results
    
## Results

* Visual trend showing how unemployment spiked during lockdown months.
* Maximum unemployment rate observed and the corresponding date.
* Predictions for upcoming unemployment rates using a simple regression model.
