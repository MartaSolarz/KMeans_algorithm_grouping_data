# K-Means algorithm #
 *Grouping data using the K-Means algorithm* 

## **List of contents:**
1. General information about the K-Means algorithm
2. Data information
3. Python modules used

![Gif](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)

Source: *https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif*

## 1. General information about the K-Means algorithm 

K-Means clustering algorithm is defined as an unsupervised learning method having an iterative process in which the dataset are grouped into k number of predefined non-overlapping clusters or subgroups, making the inner points of the cluster as similar as possible while trying to keep the clusters at distinct space it allocates the data points to a cluster so that the sum of the squared distance between the clusters centroid and the data point is at a minimum, at this position the centroid of the cluster is the arithmetic mean of the data points that are in the clusters.

Source and more information: *https://www.educba.com/k-means-clustering-algorithm/*

## 2. Data information 

Data includes Age-Adjusted Incidence Rate([rate note]) - cases per 100,000 and various statistical parameters (confidence intervals) referenced to U.S. county spatial units. They come from an external source - PostgreSQL relational database. The files contain a CSV file. Access to data obtained for the Data Science course organized by the CODE:ME foundation.

## 3. Python modules used ##
- ```pandas```
- ```create_engine``` from ```sqlalchemy```
- ```yaml```
- ```numpy```
- ```KMeans``` from ```sklearn.cluster```
- ```silhouette_score``` from ```sklearn.metrics```
- ```StandardScaler``` from ```sklearn.preprocessing``` 
- ```matplotlib.pyplot``` 

*Author: Marta Solarz*
