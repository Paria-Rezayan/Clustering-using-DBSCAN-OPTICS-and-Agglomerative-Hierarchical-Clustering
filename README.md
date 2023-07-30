# Clustering-using-DBSCAN-OPTICS-and-Agglomerative-Hierarchical-Clustering

Clustering using DBSCAN, OPTICS, and Agglomerative Hierarchical Clustering
The dataset used in this project can be found on https://www.kaggle.com/datasets/shwetabh123/mall-customers .

**Introduction:**
Clustering is a technique used in data analysis and machine learning to group similar data points together. In this project, I will use three different clustering algorithms, DBSCAN, OPTICS, and Agglomerative Clustering,, to cluster customers of a retail store based on their annual income and spending score.

**Dataset:**
I will be using a dataset containing information about customers of a mall. The dataset has the following features:
- CustomerID: unique identifier for each customer
- Genre: gender of the customer
- Age: age of the customer
- Annual Income (k$): annual income of the customer in thousands of dollars 5)Spending Score (1-100): score assigned by the retailer based on customer behavior and spending nature

**Objective:**
My objective for this project is to cluster the customers into different groups based on their annual income and spending score. This will help understand which groups of customers are more valuable to the business and how we can target them effectively.

**Methodology:**
I will be using three different clustering algorithms in this project:
1. Density-Based Spatial Clustering of Applications with Noise (DBSCAN): A density-based clustering algorithm that groups together points that are close to each other and separates them from points that are far away.
2. Ordering Points To Identify Cluster Structure (OPTICS): A density-based clustering algorithm that identifies clusters of varying densities and sizes by ordering points based on their connectivity.
3. Agglomerative Clustering: A hierarchical clustering algorithm that starts with each point as its own cluster and gradually merges them into larger and larger clusters based on their distance.

**Steps:**
The following are the steps we will follow in this clustering project:
1. Import Libraries: We will import necessary libraries such as pandas, numpy, matplotlib, and scikit-learn to perform clustering.
2. Load Data: We will load the customer dataset into a pandas dataframe and perform exploratory data analysis to get insights into the data.
3. Data Preprocessing: We will preprocess the data to remove any missing values, drop unnecessary columns, and scale the data. Visualize Data Distribution: We will create histograms to visualize the distribution of each variable in the dataset.
4. DBSCAN Clustering: We will apply DBSCAN algorithm to cluster the customers into different groups based on their annual income and spending score.
5. OPTICS Clustering: We will apply OPTICS algorithm to cluster the customers into different groups based on their annual income and spending score.
6. Agglomerative Clustering: We will apply agglomerative clustering algorithm to cluster the customers into different groups based on their annual income and spending score.
7. Visualization: We will visualize the clusters using scatter plots and other visualizations.
8. Interpretation: We will interpret the results and draw conclusions about the customer segments.
