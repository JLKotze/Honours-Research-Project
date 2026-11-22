# Predicting JSE Technology Stock Price Movements

## Overview

This research project investigates whether machine learning models can predict daily stock price movements for selected technology companies listed on the Johannesburg Stock Exchange (JSE). It compares Logistic Regression, Support Vector Machine (SVM) and Random Forest models with an ARIMA forecasting baseline.

## Repository contents

- `Research Code.ipynb` — notebook containing the analysis and modelling
- `Data/` — CSV files containing the data used by the notebook

## Getting started

Open `Research Code.ipynb` in Jupyter Notebook, JupyterLab or Google Colab. Keep the `Data/` folder alongside the notebook so the notebook can find its CSV files, then run the cells from top to bottom.

## Data and methods

The notebook uses historical stock data for Naspers, Prosus and iOCO Limited. It calculates technical indicators and evaluates the models using a chronological 80/20 training and testing split. It also examines different feature selection configurations.

## Research focus

The study compares model performance for short-term stock movement prediction in the South African technology sector. The notebook contains the analysis and results; see the relevant cells for details of the data, methods and findings.