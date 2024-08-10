# CryptoClustering

# Overview

This project applies unsupervised machine learning techniques to cluster cryptocurrencies based on their market data. The goal is to identify patterns and relationships between different cryptocurrencies and gain insights into the crypto market.

## Dataset

The dataset used for this project is a CSV file containing market data for various cryptocurrencies, including:

* Coin IDs  
* Price change percentages for timesframes of 24h, 7d, 14d, 30d, 60d, 200d, and 1Y

## Steps

Data Normalization: The data is normalized using the StandardScaler module from scikit-learn.
Elbow Method: The elbow method is used to find the optimal value for k (number of clusters) using the original scaled data.
K-Means Clustering: The K-means algorithm is applied to the original scaled data with the optimal value for k to cluster the cryptocurrencies.
PCA Dimensionality Reduction: The original scaled data is reduced to three principal components using Principal Component Analysis (PCA).
Elbow Method (PCA): The elbow method is used to find the optimal value for k using the PCA data.
K-Means Clustering (PCA): The K-means algorithm is applied to the PCA data with the optimal value for k to cluster the cryptocurrencies.
Code

## Tools:

pandas for data manipulation and analysis
scikit-learn for machine learning tasks
hvPlot for data visualization

The project produces two sets of results:

Original Scaled Data: A scatter plot showing the clusters of cryptocurrencies based on the original scaled data.
PCA Data: A scatter plot showing the clusters of cryptocurrencies based on the PCA data.
