🌳 Customer Segmentation using Agglomerative Clustering 
📌 Project Overview
For Day 6, I am exploring Hierarchical Clustering. Specifically, I implemented Agglomerative Clustering, a "bottom-up" approach where each data point starts in its own cluster and pairs are merged as one moves up the hierarchy.

🛠️ Technical Stack
Libraries: Scikit-Learn, SciPy, Pandas, Matplotlib, Seaborn.

Algorithm: Agglomerative Clustering.

Visualization: Dendrograms to determine the optimal number of clusters.

📊 Key Steps Implemented
Feature Scaling: Utilizing StandardScaler to normalize the data before clustering.

Dendrogram Analysis: Using SciPy's dendrogram function to visualize the merging process and identify the threshold for cluster selection.

Modeling: Training the AgglomerativeClustering model with the optimal number of clusters.

Cluster Visualization: Mapping the resulting segments on a scatter plot to analyze customer behavior.
