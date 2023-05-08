# cs5293sp23-project3
Template repo for Project 3

`smartcity/`  - contains the pdf applications \
`project3.ipynb` - template notebook to follow for Project3

#### Description of algorithms

<b>K-Means Algorithm:-</b> K-means is a clustering algorithm used to partition a dataset into K clusters, where K is a pre-defined number of clusters. The algorithm iteratively assigns each data point to the nearest cluster center, which is the arithmetic mean of all the data points in that cluster. This process continues until the cluster centers no longer change significantly, or a maximum number of iterations is reached. The final result is a set of K clusters, each represented by its centroid or center. K-means is widely used in machine learning and data mining for clustering, classification, and anomaly detection.

<b> Hierarchial Clustering:-</b>Hierarchical clustering is a type of clustering algorithm used in unsupervised machine learning, where the goal is to group similar objects into clusters based on their distance or similarity. In hierarchical clustering, the data points are grouped in a tree-like structure, called a dendrogram, where the objects are placed in a hierarchy based on their similarities. 

There are two main types of hierarchical clustering: agglomerative and divisive. In agglomerative clustering, each object is initially treated as a separate cluster, and then the two closest clusters are merged to form a new, larger cluster. This process is repeated until all objects belong to a single cluster. In divisive clustering, all objects start in a single cluster, and then the cluster is recursively divided into smaller and smaller clusters until each object belongs to its own cluster.

<b>DBSCAN Algorithm:-</b> DBSCAN which stands for Density-Based Spatial Clustering of Applications with Noise, is a clustering algorithm used to group together data points that are close to each other in a high-dimensional space. It is particularly useful for datasets with complex shapes, clusters of varying densities, and noisy or outlying data.

DBSCAN has several advantages over traditional clustering algorithms like k-means or hierarchical clustering. It can handle clusters of different shapes and sizes, and can automatically detect noise or outliers in the data. It does not require the number of clusters to be specified in advance, and can perform well on large datasets with many dimensions. However, it can be sensitive to the choice of parameters, particularly the eps parameter, which can greatly affect the resulting clusters.
