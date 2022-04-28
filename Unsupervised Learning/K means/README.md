## K means  
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances.   

Unlike supervised learning, unsupervised learning deals with unlabeled data. As such, the techniques used are vastly different than those found in supervised learning. Unsupervised learning typically falls within the following two reahlms:  

1. Clustering  

2. Dimensionality Reduction  
***  
### Advantages of k-means
- Relatively simple to implement.  

- Scales to large data sets.  

- Guarantees convergence.  

- Can warm-start the positions of centroids.  

- Easily adapts to new examples.  

- Generalizes to clusters of different shapes and sizes, such as elliptical clusters.  
### Disadvantages of k-means  
- Choosing  manually.  

Use the “Loss vs. Clusters” plot to find the optimal (k), as discussed in Interpret Results.  

- Being dependent on initial values.  

- Clustering data of varying sizes and density.  

k-means has trouble clustering data where clusters are of varying sizes and density. To cluster such data, you need to generalize k-means as described in the Advantages section.  
- Clustering outliers.  

Centroids can be dragged by outliers, or outliers might get their own cluster instead of being ignored. Consider removing or clipping outliers before clustering.  

- Scaling with number of dimensions.  

As the number of dimensions increases, a distance-based similarity measure converges to a constant value between any given examples. Reduce dimensionality either by using PCA on the feature data, or by using “spectral clustering” to modify the clustering algorithm as explained below.  
## Datasets
make moon dataset from scikit learn
https://scikit-learn.org/stable/modules/generated/sklearn.datasets.make_moons.html
