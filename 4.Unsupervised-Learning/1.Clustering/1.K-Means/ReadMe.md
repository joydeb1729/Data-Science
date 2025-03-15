## K-Means Clustering

### What is K-Means Clustering?
K-Means is a centroid-based clustering algorithm that partitions data into $k$ clusters. It iteratively refines cluster assignments to minimize intra-cluster variance.

### How K-Means Works
1. Choose the number of clusters ($k$).
2. Initialize $k$ centroids randomly or using the **K-Means++** method.
3. Assign each data point to the nearest centroid.
4. Update centroids as the mean of assigned points.
5. Repeat steps 3 and 4 until centroids no longer change significantly.

### Mathematical Formulation
- The objective of K-Means is to minimize the **Within-Cluster Sum of Squares (WCSS)**:
  $$
  J = \sum_{i=1}^{k} \sum_{x \in C_i} \| x - \mu_i \|^2
  $$
  where:
  - $J$ is the cost function (WCSS),
  - $C_i$ represents the set of points in cluster $i$,
  - $\mu_i$ is the centroid of cluster $i$,
  - $\| x - \mu_i \|^2$ is the Euclidean distance between a point $x$ and its assigned centroid.

### Choosing the Right $k$
The **Elbow Method** helps determine the optimal number of clusters by:
- Running K-Means for different values of $k$.
- Plotting the within-cluster sum of squares (WCSS) against $k$.
- Identifying the point where WCSS starts decreasing more slowly (elbow point).

### K-Means++ Initialization
- Instead of random initialization, **K-Means++** selects initial centroids to improve convergence and avoid poor cluster assignments.
- Ensures centroids are spread out, reducing the risk of local minima.

### Applications of K-Means
- Customer segmentation in marketing
- Image compression and segmentation
- Anomaly detection in cybersecurity
- Pattern recognition in medical diagnosis

---
This folder contains an implementation of K-Means Clustering along with explanations and practical applications.