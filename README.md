🛍️ Customer Segmentation using Clustering
📌 Overview

This project applies unsupervised machine learning techniques to perform customer segmentation on the Mall Customers dataset.
The goal is to group customers based on their annual income and spending score, helping businesses better understand their target audience and make data-driven marketing decisions.

⚙️ Dataset

File: Mall_Customers.csv

Features used:

Annual Income (k$)

Spending Score (1-100)

Gender was mapped (Male=1, Female=0) for visualization purposes.

🔑 Methods & Algorithms

The following clustering algorithms were applied and compared:

K-Means Clustering

Agglomerative Hierarchical Clustering

DBSCAN (Density-Based Spatial Clustering)

Additionally:

Dendrograms were plotted for hierarchical clustering.

Elbow Method was used to find the optimal number of clusters in K-Means.

Silhouette Score was calculated for model evaluation and comparison.

📊 Results & Visualization

Pairplots and correlation matrices to explore relationships.

Cluster visualizations for K-Means, Agglomerative, and DBSCAN.

Pie charts showing cluster distribution.

Evaluation of models using Silhouette Scores.

Model	Silhouette Score
K-Means	X.XX
Agglomerative	X.XX
DBSCAN	X.XX
🛠️ Technologies Used

Python 🐍

Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy, plotly
