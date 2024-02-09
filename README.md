# Cryptocurrency Clustering Analysis

## Overview

This project conducts an exploratory analysis of cryptocurrency market data to identify patterns and group similar cryptocurrencies using clustering algorithms. We utilize techniques such as K-Means clustering and Principal Component Analysis (PCA) to optimize our clusters and improve visualization.

## Technologies Used

-   Python
-   Pandas
-   Scikit-learn (KMeans, PCA, StandardScaler)
-   Hvplot
-   Jupyter Notebook

## Data Preparation

The data was sourced from `crypto_market_data.csv` and was normalized using `StandardScaler` from scikit-learn. We then proceeded to find the optimal number of clusters (k) using the elbow method.

## Clustering Analysis

Two K-Means models were created: one using the original scaled data and another using the PCA-reduced data. The clustering outcomes were visualized using Hvplot, allowing us to compare the results before and after applying PCA.

## Results

The optimal k values were determined for both the original and PCA-reduced datasets. We noted the differences in clustering when reducing the number of features, demonstrating the impact on cluster definition and data simplification.

## Usage

To replicate this analysis:

1.  Install the required libraries.
2.  Load the dataset into a Jupyter Notebook.
3.  Execute the cells sequentially to perform the scaling, clustering, and PCA.

## Conclusion

The visualizations and composite plots illustrate the trade-offs between feature reduction and clustering detail. This analysis aids in understanding the segmentation of cryptocurrencies based on market behavior.
