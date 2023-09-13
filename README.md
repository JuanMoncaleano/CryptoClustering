# Cryptocurrency Clustering Analysis
*Overview*

This project aims to cluster various cryptocurrencies to identify potential patterns and correlations among them. We use unsupervised learning techniques, specifically K-Means clustering, along with Principal Component Analysis (PCA) for dimensionality reduction.

*Technologies*
Python
Jupyter Notebook
Scikit-learn
Pandas
hvPlot
Matplotlib
Installation and Usage
Clone this repository and open the Jupyter Notebook (Crypto_Clustering.ipynb) in a Jupyter environment. Make sure you have installed all the libraries listed under "Technologies".

Dataset

The dataset (crypto_market_data.csv) contains various metrics for different cryptocurrencies, such as price, market capitalization, and percentage change in price over different time frames.

Steps

Data Preprocessing: The dataset is cleaned and scaled to prepare for clustering analysis.

Principal Component Analysis (PCA): PCA is performed to reduce the dimensionality of the data, making it easier to visualize and analyze.

K-Means Clustering:

The optimal number of clusters (k) is determined using the Elbow method.
The K-Means algorithm is applied to the PCA-reduced data.
Visualization:

Elbow curves for both the original and PCA-reduced data are plotted for comparison.
A scatter plot is generated to visualize the clusters.
Insights
The clusters formed through PCA-reduced data appear to be more compact, making them easier to distinguish visually. In contrast, clusters from the original data are more dispersed and show some overlapping, making immediate interpretation less straightforward.
