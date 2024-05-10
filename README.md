# Customer Segmentation Project: Unveiling Insights with K-Means Clustering
## Overview
This project focuses on utilizing K-Means clustering to segment customers based on their purchasing behaviors and preferences. By analyzing a comprehensive dataset of customer transactions, we aim to identify distinct segments within the customer base

## ⏳ Dataset
The 'Mall_Customers.csv'  file contains data on various attributes:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## :mag: Data Cleansing
* Removed non-related columns: CustomerID, Age & Gender.
* Ploted heat map for correlation matrix:

<img width="536" alt="Correlation Matrix" src="https://github.com/NadirZamouche/Customer-Segmentation/assets/95188070/4f99c2d8-bf12-4806-8352-1c3347227f1f">

Based on the image it seems that there is a very week positive relationship between the 2 columns.

## 📊 Choosing the Number of Clusters
Using the Elbow Point Graph (Cut-off Point Grapgh), I found the ideal number of clusters to be equal to 5 since it's the last elbow point where there is no sharp drop after it:

<img width="451" alt="Elbow Point Graph" src="https://github.com/NadirZamouche/Customer-Segmentation/assets/95188070/4ba76002-6b92-45b8-ae5e-7f19b8f9f6b6">


## 📈 Clusters Visualization

<img width="546" alt="Clusters" src="https://github.com/NadirZamouche/Customer-Segmentation/assets/95188070/cc40dc10-25f6-4cee-9571-3b3919ffcc08">
