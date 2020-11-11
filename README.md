# Clustering
Clustering for Outlier Analysis using Gowers Distance
Clustering algorithms work using dissimilarities or distances between objects, defined by a distance metric. 
A distance metric calculates the distance between two objects. If we cannot define the distance between objects, then we cannot perform the clustering. This issue can occur when not all data is of the same type. 

Gowers Distance was chosen because:
The standard k-means algorithm isn't directly applicable to categorical data
Sample space for categorical data is discrete, and doesn't have a natural origin. A Euclidean distance function  from K means on such a space isn't really meaningful.
