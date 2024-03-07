# Stock Price Anomaly Detection and Regression Analysis

This repository contains Python code for detecting anomalies in stock prices and performing regression analysis on the detected anomalies. It is designed to be used in Jupyter Notebook.

## Overview

The code uses various techniques, including Isolation Forest for anomaly detection and Linear Regression for regression analysis. It also includes data preprocessing steps such as data loading, transformation, and visualization.

## Dependencies

Make sure you have the following dependencies installed:

- `matplotlib`
- `pandas`
- `numpy`
- `scikit-learn`
- `seaborn`
- `yfinance`

You can install them using pip:

```bash
pip install matplotlib pandas numpy scikit-learn seaborn yfinance

## Features

## Data Loading
The load_stock_data function is used to load stock price data from Yahoo Finance. It supports various data periods and intervals.

## Anomaly Detection
Anomalies in the stock price data are detected using the Isolation Forest algorithm. Anomalies are visualized and analyzed using clustering scores.

## Regression Analysis
Regression analysis is performed on the detected anomalies using Linear Regression. The regression line is plotted along with the anomalous prices.

Keep in mind that linear regression might not be optimal for this case; it's an experiment.
