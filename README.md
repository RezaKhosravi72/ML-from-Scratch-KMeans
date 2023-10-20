# K-Means Clustering from Scratch

## Project Overview:

The "K-Means Clustering from Scratch" project demonstrates the implementation of the K-Means clustering algorithm in Python without relying on external libraries. K-Means is a popular unsupervised machine learning technique used to partition data into groups or clusters based on similarity.

## Implementation Details:

#### Custom K-Means Class:

- The project features a custom K-Means class for K-Means clustering.

#### Constructor:

- The K-Means class is initialized with parameters such as the number of clusters (K), the maximum number of iterations (max_iters), and whether to plot the steps (plot_steps).

#### Methods:

- predict(X): Clusters data points into K clusters.
- _get_cluster_labels(clusters): Assigns cluster labels to each data point.
- _create_clusters(centroids): Assigns data points to the closest centroids.
- _closest_centroid(sample, centroids): Identifies the closest centroid to a data point.
- _get_centroids(clusters): Calculates new centroids based on the data points in each cluster.
- _is_converged(centroids_old, centroids): Checks if the algorithm has converged.

#### Plotting:

- The project provides an optional visualization of data points and centroids during clustering.
- Data points are plotted in different colors to represent cluster assignments, and centroids are marked with "x."

### Code Overview:

- A custom K-Means class is developed to perform K-Means clustering without external libraries.
- The project generates synthetic data using make_blobs from scikit-learn.
- K-Means is applied to cluster the data into three clusters (centers=3).

#### Key Takeaways:

- This project showcases the ability to implement a fundamental machine-learning algorithm from scratch.
- The custom K-Means class is designed to be highly flexible, allowing the user to specify key parameters.
- The optional step-by-step visualization aids in understanding the clustering process.


On the whole, this practical project of mine demonstrates my strong grasp of machine learning algorithms, data processing, and coding skills in Python. It emphasizes my ability to work with numerical data and perform complex mathematical operations.
