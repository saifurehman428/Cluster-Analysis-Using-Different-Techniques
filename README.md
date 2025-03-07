# Clustering Analysis Using Different Techniques

This project applies various clustering algorithms to a dataset with known labels to evaluate how closely the clustering results match the original clusters. The clustering algorithms used in this project are:

- Birch
- DBScan
- Agglomerative Clustering
- KMedoids
- KModes

## Dataset

The datasets used in this project contain labels, which allow us to compare the performance of different clustering algorithms against the true clusters. Each dataset is loaded and preprocessed before applying the clustering algorithms.

![orignal](images/orignal.png)

## Clustering Algorithms

### Birch (Balanced Iterative Reducing and Clustering using Hierarchies)
Birch is a hierarchical clustering algorithm that builds a tree structure called the Clustering Feature Tree (CF Tree) for incremental clustering of incoming, multi-dimensional metric data points.

![birch](images/birch.png)

### DBScan (Density-Based Spatial Clustering of Applications with Noise)
DBScan is a density-based clustering algorithm that can discover clusters of arbitrary shape and is robust to noise. It requires two parameters: epsilon (ε) and the minimum number of points required to form a dense region.

![DBScan](images/DBScan.png)

### Agglomerative Clustering
Agglomerative Clustering is a hierarchical clustering method that builds nested clusters by merging or splitting them successively. This project uses the linkage criteria to determine the distance between clusters.

![Agglomerative](images/Agglomerative.png)

### KMedoids
KMedoids is a clustering algorithm related to k-means and the medoidshift algorithm. It represents clusters by their medoid, the object in a cluster whose average dissimilarity to all the objects in the cluster is minimal.

![KMedoid](images/KMedoid.png)

### KModes
KModes is used for clustering categorical data. It is an extension of the k-means algorithm to cluster categorical data by replacing the means of clusters with modes.

![Kmodes](images/Kmodes.png)

## Evaluation

The performance of each clustering algorithm is evaluated by comparing the predicted cluster labels with the true labels. The results show that the clusters made using Birch are close to the orignal clusters.

## Usage

To run the clustering analysis, execute the following steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/clustering-analysis.git
   cd clustering-analysis
