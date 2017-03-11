# Dominant-Color-Extraction

K-means is a clustering algorithm that generates k clusters based on n data points. The number of clusters k must be specified ahead of time. Although algorithms exist that can find an optimal value of k.

In order to find the most dominant colors in our image, we treated our pixels as the data points and then applied k-means to cluster them.

We used the scikit-learn implementation of k-means to avoid having to re-implement it.

Requirements:

1. Numpy
2. OpenCV
3. K-Means Clustering 
4. Scikit
