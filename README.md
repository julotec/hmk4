# Bike Rental Data Analysis

## Description

This repository contains Python code for analyzing bike rental data. The dataset includes calendar information, weather conditions, and the number of bikes rented on a given day. The aim of the analysis is to predict the number of bike rentals based on various features.

## Files

- `bikes_rent.csv`: CSV file containing the data for analysis.

## Table of Contents

1. [Exploratory Data Analysis](#exploratory-data-analysis)
2. [Feature Correlations](#feature-correlations)
3. [Linear Regression](#linear-regression)
4. [Regression with Regularization](#regression-with-regularization)
5. [Cross-Validation](#cross-validation)
6. [Conclusions](#conclusions)

## Exploratory Data Analysis

We load the data from the `bikes_rent.csv` file using the pandas library and display the first 5 rows.

```python
import pandas as pd

df = pd.read_csv("bikes_rent.csv")
print(df.head())
