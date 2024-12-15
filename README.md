# Predicting Stock Prices

## Research Question
What are the future open prices of MSTR for the next 365 days?

## Data and Methodology
This project predicts the future open prices of MSTR (MicroStrategy) using historical data and Bitcoin's influence on MSTR stock value. The methodology follows a recursive approach, where predictions for the next 30 days are made based on the past 90 days of data. After each prediction, the oldest 30 days are removed and replaced with the newly predicted values, continuing the iterative process to forecast 365 days in total.

Bitcoin Data: Bitcoin data is incorporated into the model because MicroStrategy purchases Bitcoin with debt, and Bitcoin’s value significantly impacts MSTR stock.

## Features Used:
Daily open, high, low, and close prices, Daily volume, 2-day and 15-day Exponential Weighted Moving Averages (EWMA), which are particularly useful for capturing short-term trends, especially considering the volatility of both Bitcoin and MSTR.
