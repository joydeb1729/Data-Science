# Hierarchical Clustering

## Introduction
Hierarchical clustering is a type of unsupervised machine learning algorithm used for grouping data into clusters. Unlike K-Means, it does not require specifying the number of clusters beforehand. Instead, it creates a hierarchy of clusters that can be visualized using a **dendrogram**.

## Types of Hierarchical Clustering
1. **Agglomerative Hierarchical Clustering** (Bottom-up approach):
   - Starts with each data point as an individual cluster.
   - Merges the closest clusters step by step.
   - Continues until all points are in a single cluster or a stopping criterion is met.
   
2. **Divisive Hierarchical Clustering** (Top-down approach):
   - Starts with all data points in one cluster.
   - Splits clusters recursively into smaller clusters.
   - Continues until each data point is its own cluster or a stopping criterion is met.

## Dendrogram
A **dendrogram** is a tree-like diagram that represents the process of hierarchical clustering. It shows how clusters are merged or divided at different levels, helping determine the optimal number of clusters by identifying the largest vertical distance without merging.

## Measuring Distance Between Clusters
Different methods exist to measure the distance between two clusters:

1. **Single Linkage** (Minimum distance)
   - The distance between two clusters is the shortest distance between any two points in the clusters.
   - Can create elongated clusters and is sensitive to noise.

2. **Complete Linkage** (Maximum distance)
   - The distance between two clusters is the farthest distance between any two points in the clusters.
   - Tends to create compact clusters.

3. **Average Linkage** (Mean distance)
   - The distance between two clusters is the average distance between all pairs of points in the clusters.
   - Balances the properties of single and complete linkage.

4. **Centroid Linkage** (Centroid distance)
   - The distance between two clusters is the distance between their centroids (mean points).
   - Can be unstable if the clusters are not compact.

## Advantages of Hierarchical Clustering
- No need to predefine the number of clusters.
- Can produce a hierarchical structure that provides insights into the data.
- Suitable for small datasets with clear hierarchical relationships.

## Disadvantages
- Computationally expensive (O(n^2) or O(n^3) complexity).
- Sensitive to noise and outliers.
- Cannot handle large datasets efficiently.

## Applications
- Document and text clustering
- Image segmentation
- Genomic data analysis
- Social network analysis

## Conclusion
Hierarchical clustering is a powerful technique for clustering data based on similarity. The **dendrogram** provides a useful way to visualize clustering, while different linkage methods influence the shape and composition of the clusters. The choice between **agglomerative** and **divisive** depends on the dataset and the desired clustering structure.

