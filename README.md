# Customer Segmentation with Clustering Algorithms

This repository explores customer segmentation using three powerful clustering algorithms: K-Means, DBSCAN, and Hierarchical Clustering. By clustering customers based on their demographic attributes and spending behavior, the project aims to uncover distinct customer segments that can inform targeted marketing strategies and improve customer engagement.

## Dataset

The dataset used in this project contains 200 customer records with the following features:

CustomerID: Unique identifier for each customer

Gender: Customer's gender

Age: Customer's age

Annual Income (k$): Customer's annual income in thousands of dollars

Spending Score (1-100): Customer's spending score based on their purchasing behavior

## Methods

K-Means: Partitioning method that aims to divide customers into K clusters where each customer belongs to the cluster with the nearest mean.

DBSCAN: Clustering algorithm that identifies clusters of varying shapes and sizes in the presence of noise.

Hierarchical Clustering: Agglomerative clustering method that builds clusters by merging or splitting them based on their distances.

## Implementation
The project is implemented in Python using Jupyter notebooks. Each clustering algorithm is applied to the dataset to identify customer segments. The steps include data preprocessing, feature selection, standardization, clustering model fitting, and evaluation.

## Evaluation
Silhouette Score: Measure of how similar an object is to its own cluster compared to other clusters. Higher silhouette scores indicate better-defined clusters.

## Contributing
Contributions to this project are welcome. If you have suggestions or improvements, please fork the repository, create a pull request, and we will review it together.
