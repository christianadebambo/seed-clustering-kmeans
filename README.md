# Seed Clustering

This repository contains code for clustering seeds using the K-Means algorithm. The goal is to group the seeds in such a way that seeds within the same cluster are similar to each other while seeds in different clusters are distinct.

Dataset taken from [UCI ML Repository](https://archive.ics.uci.edu/dataset/236/seeds)

## Prerequisites

Before running the code, ensure that you have the following libraries installed:

- numpy
- pandas
- matplotlib
- scikit-learn

## Code Explanation

The code performs the following steps:

- Imports the necessary libraries for data processing, visualization, and clustering.
- Loads the seed dataset and assigns appropriate column names.
- Performs K-Means clustering on the dataset with a specified number of clusters.
- Updates the cluster labels for better visualization.
- Calculates the accuracy of the clustering by comparing the predicted labels with the actual labels in the dataset.
- Performs K-Means clustering on a subset of features (area and length) and visualizes the labels and predictions.
- Manually implements the K-Means algorithm by defining functions for finding centroids, assigning data points to the nearest centroids, and calculating new centroids based on the assigned data points.
- Visualizes the clustering results using scatter plots.
- Creates a Voronoi diagram to visualize the clusters using PCA to reduce the dimensionality of the dataset.
- Visualizes the seed dataset in high-dimensional space using a 3D scatter plot.

## Results

The code provides the clustering results and accuracy metrics, allowing you to assess the effectiveness of the K-Means algorithm in grouping similar seeds together. The visualizations help in understanding the clusters and identifying patterns within the dataset.

## Instructions

To run the project code, follow these steps:

- Download the dataset.
- Install the required dependencies mentioned in the Prerequisites section.
- Run the code in a Python environment that supports Jupyter notebooks or execute the code in a Python script.

Note: Adjustments may be required in the code paths to ensure proper loading of the dataset.

Happy clustering!
