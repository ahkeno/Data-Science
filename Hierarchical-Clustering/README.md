Hierarchical Clustering, an unsupervised machine learning technique used to identify groups of similar observations.

The practice uses a small banking customer dataset to understand how customers can be grouped based on behavioral features such as monthly spending and transaction frequency.

🎯 Learning Objectives
Understand the concept of Hierarchical Clustering
Learn how Agglomerative Clustering works
Understand distance and linkage methods
Learn the concept of Ward linkage
Generate and interpret a dendrogram
Understand how a dendrogram can help determine the number of clusters
Practice Python implementation using scikit-learn and scipy
🧠 Theory

Hierarchical Clustering creates a hierarchy of clusters by progressively grouping observations based on their similarity.

In this practice, I focus on Agglomerative Hierarchical Clustering:

Individual Customers
↓
Calculate Distance
↓
Merge Similar Customers
↓
Merge Similar Clusters
↓
Build Hierarchy
↓
Dendrogram
↓
Determine Clusters
Ward Linkage

Ward linkage merges clusters in a way that minimizes the increase in within-cluster variance.

This is useful when we want relatively compact and homogeneous clusters.

📊 Dataset

A small simulated banking customer dataset is used for learning:

Monthly Spending
Transaction Frequency

The dataset is intentionally simple so that the clustering process and dendrogram can be easily understood.

🛠️ Technologies
Python
Pandas
NumPy
Matplotlib
SciPy
Scikit-learn
Jupyter Notebook
🔬 Workflow

The notebook follows these steps:

Import Python libraries
Create the customer dataset
Select clustering features
Standardize the features
Apply Hierarchical Clustering
Generate the linkage matrix
Create a dendrogram
Interpret customer similarity
Explore possible cluster divisions
📈 Understanding the Dendrogram

The dendrogram visualizes how observations are progressively merged into clusters.

The vertical height at which two branches merge represents their distance or dissimilarity.

Lower merge → more similar observations
Higher merge → more different observations

A horizontal cut across the dendrogram can be used to identify a possible number of clusters.
