# CryptoClustering

## Overview
A multi-dimensional dataset is subjected to clustering, both before and after reducing dimensionality using PCA.

## Method
First, use the elbow curve to select the optimal number of clusters to use for the K-means model. Run the model using that K value, then depict the clustering in 2-D space along one set of selected axes.
Then, repeat this process after performing PCA on the dataset in order to reduce the number of dimensions.

## Conclusion and Adjustment
For this dataset, PCA did result in better inter-cluster separation, while intra-cluster compactness seemed to be largely unaffected. It seems that PCA preserved much of the dataset's characteristics while simplifying the dataset from 7 to 3 dimensions.
