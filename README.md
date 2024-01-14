# CryptoClustering

GitHub Repo Link: https://github.com/a-dhil/CryptoClustering
Crypto_Clustering: Crypto_Clustering.ipynb This is the main file inside the folder.
Resource: This folder contains the data used for this analysis.

# About this challenge

In this challenge, the knowledge of Python and unsupervised learning was applied to cluster crypto currencies data. K-mean was the method used to get the analysis. Elbow method is applied to choose optimal number of clusters and PCA technique was used to reduce number of features in dataset.

# Steps followed in this model

1.Prepare the data (by scaling it)
2.Find the value of k using original data
3.Cluster Cryptocurrencies with K-means
4.PCA to optimize clusters
5.Find value of k from PCA data
6.Cluster using PCA data

# Python libraries used

import pandas as pd
import hvplot.pandas
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler

# Conclusion

PCA helps in orginaizing clusters more into define groups, given the risk of loosing some data.