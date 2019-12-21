## The Oscars

## NBA Dataset Regression

Resource: https://projects.fivethirtyeight.com/nba-model/nba_elo.csv

The dataset contains game-by-game Elo ratings and forecasts back to 1946. As a fan of Kobe Bryant, I choose NBA dataset for investigation. his project functions as an extention to the major league project. In this project, i only focus on Team Lakers. The most splendid period for Lakers are 2000 to 2002 and 2009 to 2010. So i decide to choose 2000 to 2010 as the time to investigate. Classification, time series forecasting methods are applied:

    1. Classification 
      1.1 Random Forest 
      1.2 KNN
      1.3 Neural Network
    2. Time Series Forecasting  
      2.1. Prophet
      2.2. Sarima 

## Purpose:
   To determine if lakers could win the game!

## Main steps:
   1. Data Cleaning
   2. Feature correlation
   3. Randmon forest, KNN, Neural network classifiers are applied
   4. Prophet and sairma time series forecasting models are applied

## Result:
    Classification:
     1. KNN Accuracy              : 68.5%
     2. Neural Network Accuracy   : 66.50% 
     3. Random Forest Accuracy    : 66.49%

## Project Structure

```bash

.
├── notebooks 
│     └── The Oscars.ipynb
├── README.md
└── data
      └── nba_elo.csv
```
