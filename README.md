#  Segmentation of Ecommerce brand customers using RFM, KMeans and Predicting Customer Lifetime Value

# K-Means Clustering-Customer Segmentation

In this project we have used multiple approaches for clustering to segment the cusomers of Ecommerce company into distinct groups based on specified features. The goal is to group data points so that points within a group are more similar to each which basically shows the types of customers.

**Table of Contents**

Project Overview

Dataset

Dependencies

Exploratory Data Analysis (EDA)

KMeans Clustering Process

Model Evaluation

Results and Interpretation


**Project Overview**

This project applies the KMeans clustering algorithm to group data points based on certain attributes. Clustering is useful in applications such as customer segmentation, image compression, and anomaly detection. In this project, we utilize KMeans to cluster segment the customers, which may help in developing targeted strategies or further predictive analytics.

**Dataset**


**Dependencies**

Ensure you have the following dependencies installed:

* Python 3.x
* numpy
* pandas
* matplotlib
* seaborn
* scikit-learn

**Exploratory Data Analysis (EDA)**

* Data Cleaning: Handling missing values, outliers,datetime column 
* Understanding how Many Customers Acquired Every Month
* Retention of Customers on Month-on-Month Basis
* Revenue Analysis from Existing and New Customers
* KPI: Revenue, number of orders, average order value, number of customers, quantity

**Data Visualization**

* Trends by category and location
* Seasonality by month
* How number order varies and sales with different day
* Revenue, Marketing spend, percentage of marketing spend out of revenue, Tax, percentage of delivery charges by month
* Monthly revenue, marketing spend, tax, and delivery charges
* Calculate the correlation between Total Marketing Spend and Total Revenue
* Product that appeared in the transactions
* Product  purchased mostly based on the quantity

**Heuristic segmentaion (Value based, RFM-Recency, Frequency, Monetary)**


















**Feature Selection**

Choosing relevant features for clustering using Principal Component Analysis

**KMeans Clustering Process**

Determining the Optimal Number of Clusters:

The Elbow method and Silhouette analysis were used to determine the ideal number of clusters. Both methods help balance the model complexity and cluster cohesion.

**Fitting the Model**
   
The KMeans algorithm was applied to the selected features of the dataset. The key parameters were:

n_clusters: Optimal number determined from the Elbow method.

random_state: Ensures reproducibility.

**Visualizing the Clusters**

After fitting, we plotted the clusters using PCA (Principal Component Analysis) to reduce the data to two dimensions for visualization. This helps in understanding how well-separated the clusters are.

**Model Evaluation**

Several metrics were used to assess the clustering performance:

Inertia: Measures within-cluster variance; lower values indicate tighter clusters.

Silhouette Score: Measures how similar an object is to its own cluster compared to other clusters; higher values indicate well-defined clusters.

Cluster Centers: Analyzing the cluster centroids to understand the main characteristics of each cluster.

**Predicting segment for new data**






