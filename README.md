# Clustering Analysis

## Overview

This project focuses on **unsupervised learning techniques**, specifically **K-Means and Agglomerative Clustering**, to identify patterns in a **shill bidding dataset**. The goal is to detect fraudulent bidding behavior in online marketplaces.

## Features

- **Data Preprocessing**: Handling missing values, feature scaling, and encoding.
- **Clustering Algorithms**:
  - **K-Means Clustering**: Optimising the number of clusters using the **Elbow Method**.
  - **Agglomerative Clustering**: Hierarchical clustering with **dendrogram analysis**.
- **Evaluation Metrics**: Silhouette Score, Davies-Bouldin Index.
- **Data Visualisation**: Cluster distribution using **scatter plots and heatmaps**.

## Requirements

- Python 3.x
- Libraries: `numpy`, `pandas`, `scikit-learn`, `matplotlib`, `seaborn`
- Jupyter Notebook

## Usage

1. Open `clustering.ipynb` in Jupyter Notebook.
2. Run the cells sequentially to **load data, preprocess, apply clustering algorithms, and evaluate performance**.
3. Visualise the clustered data to interpret patterns and potential fraudulent activities.

## Results

- Identified **optimal cluster groups** representing different types of bidders.
- Detected potential **fraudulent bidding behaviors** based on clustering insights.

## References

- Dataset: **Shill Bidding Dataset** (UCI Machine Learning Repository)
- Clustering techniques from **scikit-learn** for anomaly detection.

---

