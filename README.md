# Mall_Shopper_Segmentation


## 📌 Project Overview

This project applies **unsupervised machine learning** techniques to cluster mall customers based on their demographic and spending behavior. The clustering helps in customer segmentation, which can be valuable for marketing and business decision-making.

## 🏷️ Dataset

The dataset consists of mall customer information, including:

- **Customer ID** (Unique identifier)
- **Gender** (Male/Female)
- **Age** 
- **Annual Income**
- **Spending Score** (Customer engagement metric)

## 📊 Clustering Techniques Used

We employed multiple clustering techniques to analyze and segment the customers:

1. **K-Means Clustering**  
   - Used the **Elbow Method** to determine the optimal number of clusters.
   - Implemented `KMeans` from `sklearn.cluster`.

2. **Hierarchical Clustering (Agglomerative Clustering)**  
   - Utilized Ward's method and Euclidean distance.
   - Generated a **dendrogram** to visualize the clustering hierarchy.

3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**  
   - Experimented with different values for `eps` and `min_samples` to identify clusters.
   - Focused on finding natural cluster patterns, even in noisy data.

## 📈 Visualizations

The project includes the following visualizations:

- **Elbow Method Graph** (Used to find the optimal number of clusters for K-Means)
- **Dendrogram** (For hierarchical clustering)
- **DBSCAN Scatter Plot** (Visualizing density-based clusters)


