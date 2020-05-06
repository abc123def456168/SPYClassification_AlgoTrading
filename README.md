# SPYClassification_AlgoTrading
Educational algorithmic trading program using machine learning to predict classification of SPY ETF price movement. (nonprofitable)

## Introduction
In this project I attempted to predict the classifaction of the price movement of the SPY ETF. A classifaction of 1 was assigned to increases in price and 0 was assigned to no change or decreases in price. There are two notebooks, and two datasets. One notebook and dataset is by 10 minute time periods and the other is by 1 minute time periods. 
  - note: The 1 minute time period script is not trained and tested, but programming is completed. The rest of this README will talk about results from the 10 min notebook.

## Data
Data was sourced from barchart.com. The data only open, high, low, close, volume, change. Target creation was applied to turn the price movement (change) into a binary classification and Feature Engineering was used to implement technical indicators.

## Model
Academic literature indicated that an ensemble of Convolutional Neural Networks and Long Short-Term Memory Networks produced results beating state of the art architectures for multivariate time series classification problems.

## Results
The model does not have any predicctive power. The model is unable to predict price decreases or no changes in price. Meaning the model only predicts that price will continue to increase each time period. Use of this model in trading will surely result in losses.

## Further Developments
To further develop this model, more sufficient data is needed (alternative data, earnings reports, etc). Additionally expansion into different markets and high frequency trading can be implemented.
