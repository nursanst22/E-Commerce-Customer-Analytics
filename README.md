**E-Commerce Customer Segmentation Using Integrated RFM Analysis and Clustering Algorithms**

This repository contains the dataset and analytical code for a research project focused on customer segmentation in the e-commerce industry. The project utilizes the Knowledge Discovery in Databases (KDD) methodology to transform raw transactional data into actionable strategic insights.

The objective of this research is to identify distinct customer behavior patterns by integrating **RFM (Recency, Frequency, Monetary)** analysis with unsupervised machine learning algorithms. The study compares the performance of four clustering models **K-Means, DBSCAN, Gaussian Mixture Model (GMM), and Mean-Shift** to determine the most effective method for customer profiling.

**Dataset Description**
The dataset used in this project consists of over **250,000 transaction records** from an e-commerce platform. It includes key variables such as:
1. Transaction dates and customer identifiers.
2. Product quantities and unit prices.
3. Geographical and demographic data.
*Note: The dataset has undergone rigorous preprocessing, including handling missing values and outlier detection to ensure the integrity of the clustering results.*

** Methodology**
This project follows the **KDD (Knowledge Discovery in Databases)** stages:
1.  Data Selection: Identifying relevant data subsets.
2.  Preprocessing: Cleaning and handling noise or inconsistent data.
3.  Transformation: Normalizing data and calculating RFM scores.
4.  Data Mining: Implementing clustering algorithms and Dimensionality Reduction using **Principal Component Analysis (PCA)**.
5.  Evaluation: Validating clusters using Silhouette Score, Davies-Bouldin Index (DBI), and Calinski-Harabasz Index (CHI).

## Key Findings
1. The **K-Means algorithm** was identified as the optimal model for this dataset, achieving a Silhouette Score of 0.38.
2. Customers are categorized into three primary segments: **Champions, Potential Loyalists, and At-Risk Customers**.
3. The results provide a basis for data-driven marketing strategies, such as loyalty programs and customer reactivation campaigns.

## Technologies Used
1. R Programming Language: Used for data manipulation, statistical analysis, and machine learning implementation.
2. Libraries: tidyverse, cluster, factorextra, and mclust.
3. Analysis Tools: RFM analysis and PCA.

## Maintenance and Contributions
This project was independently developed as a final research thesis by:
Nur Sa'diah Nasution – Lead Data Analyst Responsibilities included end-to-end data processing, algorithm benchmarking, and strategic interpretation of the results.

