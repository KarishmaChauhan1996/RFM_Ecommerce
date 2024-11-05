#  Segmentation Customers using RFM, KMeans and Predicting Customer Lifetime Value

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

This project applies multiple  KMeans clustering algorithm to group data points based on certain attributes. Clustering is useful in applications such as customer segmentation, image compression, and anomaly detection. In this project, we utilize KMeans to cluster segment the customers, which may help in developing targeted strategies or further predictive analytics.

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

* Value-based segmentation- recency, Frequency, Monetary
    - Based on Invoice value we divided customers into segments
    

**KMeans Clustering Process**

Determining the Optimal Number of Clusters:

The Elbow method and Silhouette analysis were used to determine the ideal number of clusters. Both methods help balance the model complexity and cluster cohesion.

**Fitting the Model**
   
The KMeans algorithm was applied to the selected features of the dataset. The key parameters were:

n_clusters: Optimal number determined from the Elbow method.

random_state: Ensures reproducibility.

**Visualizing the Clusters**

After fitting, we plotted the clusters using PCA (Principal Component Analysis) to reduce the data to two dimensions for visualization. This helps in understanding how well-separated the clusters are.

**Apply K-Means with the selected number of clusters (4)**

**Adding descriptive labels for each cluster based on the mean values**
   -Premium
   -Gold
   -Silver

**Insights and Interpretation**

* Defining marketing strategies based on customers profile

**Predicting Customer Lifetime Value (Low Value/Medium Value/High Value)**

**Cross Selling( Which products are selling together)**

**Predicting Next Purchase Day(How soon each customer can visit the store).**

**Cohort Analysis**











