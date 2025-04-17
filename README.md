# Credit Card Customer Segmentation Using KMeans Clustering

## Introduction

This project aims to create customer segments based on credit card usage behavior utilizing clustering analysis. The analysis employs a dataset sourced from Google Cloud, containing transactional information from bank credit card holders over the last six months. Segmentation is beneficial to help banks optimize marketing strategies and enhance customer service by addressing distinct behaviors within different customer groups.

## Main Features

- Data Cleaning (handling missing values and outliers)
- Exploratory Data Analysis (EDA)
- Feature Scaling (StandardScaler)
- Dimensionality Reduction (Principal Component Analysis - PCA)
- KMeans Clustering Analysis
- Clustering Evaluation (Silhouette Score)

## Methodology

The methodology includes data extraction from Google BigQuery, thorough data preprocessing to handle missing values and outliers, exploratory analysis to identify data distributions, feature scaling to standardize the data, PCA for dimensionality reduction, and finally, applying KMeans clustering to segment customers. Silhouette analysis was employed to determine the optimal number of clusters and validate clustering quality.

## Results

After processing and analyzing the dataset, KMeans clustering was conducted resulting in well-defined customer segments. The optimal cluster number was determined using the silhouette score, ensuring balanced intra-cluster similarity and inter-cluster differences. Customers were segmented distinctly based on behaviors such as credit balance, cash advances, frequency of purchases, and payments. Analysis revealed clear behavioral patterns; for instance, a substantial number of customers preferred cash advances over regular purchases, and most customers maintained relatively low account balances. These insights are critical for targeted marketing campaigns and service optimization.

## File Descriptions

- `Credit_Card_Customer_Segmentation_Using_KMeans_Clustering.csv`: Cleaned dataset used for analysis.
- `Credit_Card_Customer_Segmentation_Using_KMeans_Clustering.ipynb`: Jupyter notebook containing data processing, EDA, PCA, clustering, and model evaluation.
- `Credit_Card_Customer_Segmentation_Using_KMeans_Clustering_Inference.ipynb`: Notebook used to apply the trained model to new data and demonstrate inference workflow.
- `list_used_col.txt`: Text file listing the columns selected as features for the clustering model.
- `model_kmeans.pkl`: Pickle file containing the trained KMeans clustering model.
- `model_pca.pkl`: Pickle file containing the PCA transformation model used for dimensionality reduction.
- `model_scaler.pkl`: Pickle file containing the StandardScaler model used for feature scaling.
- `README.md`: This documentation file describing the project overview, methodology, and results.

