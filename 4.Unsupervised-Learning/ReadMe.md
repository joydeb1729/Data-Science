# Unsupervised Learning Algorithms

### What is Unsupervised Learning?
Unsupervised learning is a type of machine learning where models learn patterns and structures from unlabeled data. Unlike supervised learning, there are no predefined output labels, and the algorithm attempts to find hidden structures in the data.

### Classification of Unsupervised Learning
Unsupervised learning can be broadly classified into two main categories:

1. **Clustering**: The algorithm groups similar data points into clusters based on their inherent patterns. Common clustering techniques include:
   - K-Means Clustering
   - Hierarchical Clustering
   - DBSCAN (Density-Based Spatial Clustering of Applications with Noise)

2. **Association Rule Learning**: These techniques find relationships between variables in large datasets. Common association rule learning methods include:
   - Apriori Algorithm

### Common Unsupervised Learning Algorithms
Here are some of the most commonly used algorithms in unsupervised learning:

#### 1. K-Means Clustering
- A centroid-based clustering algorithm that partitions data into `k` clusters.
- Iteratively updates cluster centroids to minimize intra-cluster variance.

#### 2. Hierarchical Clustering
- Builds a hierarchy of clusters using either agglomerative (bottom-up) or divisive (top-down) approaches.
- Does not require specifying the number of clusters beforehand.

#### 3. DBSCAN
- A density-based clustering algorithm that groups points closely packed together and marks outliers as noise.
- Does not require specifying the number of clusters explicitly.

#### 4. Apriori Algorithm
- A popular association rule learning algorithm used to find frequent itemsets in transactional datasets.
- Uses a bottom-up approach to generate association rules.

#### 5. Principal Component Analysis (PCA)
- A dimensionality reduction technique that transforms data into a set of orthogonal components.
- Helps in reducing computational complexity while retaining maximum variance.

### Applications of Unsupervised Learning
Unsupervised learning techniques are widely used in various fields, such as:
- Customer segmentation in marketing
- Anomaly detection in fraud detection and cybersecurity
- Image compression and feature extraction
- Recommendation systems
- Market basket analysis and product recommendations

---
This folder contains implementations of various unsupervised learning algorithms along with explanations and practical applications.

