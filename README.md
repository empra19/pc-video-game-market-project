# Unsupervised Learning on PC Video Game Market Data

## Overview

The purpose of this project is to use various unsupervised learning methods to categorise PC games based on multi-dimensional data without pre-defined labels. This allows for the discovery of hidden relationships within gaming data.

## Data Sources

Data was sourced from Steam, the largest PC gaming storefront, and Metacritic, the foremost video game review aggregation site, combining market metrics (price, sales) with reviewer feedback (user and critic scores).

- [Steam Dataset](https://www.kaggle.com/datasets/fronkongames/steam-games-dataset/data)  
- [Metacritic Dataset](https://www.kaggle.com/datasets/brunovr/metacritic-videogames-data)

## Key Findings

The analysis successfully identified distinct clusters of games, key features driving the categorisation, and characterized each cluster in terms of these features. These clusters can be used in game recommendation systems for a better user experience. Compared to a simple genre-based recommendation system, the clustering increased the diversity of recommendations by 20%.

- [View the full project report here](FINAL%20REPORT_1.pdf)
- [View the results section here](FINAL%20REPORT_1.pdf#page=X)

## Visualisations

### Cluster Visualisation using Principal Component Analysis

This graph visualises the seven clusters after applying PCA to reduce the feature space to two dimensions for visualisation purposes. While there appears to be some overlap due to dimensional reduction, the high silhouette score (0.65) confirms that the clusters are well-separated in the full feature space.

![Cluster Visualisation using Principal Component Analysis](graphs/cluster_pca.png)

### Feature Importance for Clustering

Release date emerged as the most important feature, followed by percentage of positive Steam reviews and Metacritic critic score. The prominence of release date likely reflects technological and graphical advances over time - games from similar periods naturally share common characteristics and design philosophies shaped by the technology available when they were developed.

![Feature Importance](graphs/feature_importance.png)
