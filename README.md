# Credit Customer Segmentation with K-Means

![image](https://github.com/jeizzynab/credit-customer-segmentation/blob/44b7277318bd071523b42d258aa4ac28f65a8571/clustering.png)

### K-Means
K-Means  a widely used clustering algorithm in machine learning and statistics. Its primary purpose is to group data points into a predefined number of clusters (
𝑘
k) based on their similarity. It is an unsupervised learning algorithm, meaning it does not rely on labeled data for training.

### How K-Means Works

1. Choose the Number of Clusters (𝑘):
  Decide how many clusters you want the data to be divided into.

2. Initialize Centroids:
  Randomly select 𝑘 points in the dataset as initial "centroids" (the centers of the clusters).
  
3. Assign Data Points to Clusters:
  Each data point is assigned to the nearest centroid based on a distance metric, usually Euclidean distance.

4. Update Centroids:
  Recalculate the centroids of each cluster by finding the mean of all data points assigned to that cluster.

5. Iterate:
Repeat the process of assignment and centroid updating until the centroids no longer change significantly (convergence) or a maximum number of iterations is reached.

