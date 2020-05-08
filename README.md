# Anomaly-Detection-in-Heat-Experiments
Identification of unexpected events in a dataset from any industry is significantly important to be capture outliers such that the data so obtained can be used for analysis as normal and expected.

## Pre-processing
The dataset comprises of real-world measurements of heat experiments of a steel furnace. The various features X1-X8 are vibration reading from various positions. Since the steady state conditions are more likely to be correct, the data is first filtered for sds_armed=1.

For the above dataset the data from various experiments is then merged to one, and split into train and test sets. This data is then normalised using MinMaxScaler, and used to predict the test set for model accuracy in case of supervised learning algorithm.

## Prediction Models
1.  Supervised Anomaly Detection
    - Multivariate Gaussian based model
    - XGBoost Classification model
2.  Unsupervised Anomaly Detection
    - K-means clustering

## Accuracy Measures for Comparison
1. F1-score
1. Detection Rate
1. False Alarm Rate
