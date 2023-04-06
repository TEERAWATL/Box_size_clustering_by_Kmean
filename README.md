# Box Size Clustering using K-Means and Davies-Bouldin Index

Cluster box sizes into different groups using K-Means clustering and Davies-Bouldin Index for selecting the optimal number of clusters.

## Description

This project aims to cluster box sizes into different groups using K-Means clustering. The optimal number of clusters is determined using the Davies-Bouldin Index. The results are visualized using matplotlib.

Usage
Run the main script to execute the project:
Box_sizes_k_means_culstering_DB_index.ipynb

Dependencies
The project requires the following libraries:

pandas
numpy
scikit-learn
matplotlib
Install the dependencies using the following command:
pip install pandas numpy scikit-learn matplotlib

Dataset Preparation
Collect and organize box size data.
Load the dataset using pandas.
Data Preprocessing
Preprocess the data by handling missing values and scaling the data using suitable methods from scikit-learn or pandas.
Model Training
Train a K-Means clustering model using scikit-learn.
Determine the optimal number of clusters using the Davies-Bouldin Index.
Model Evaluation
Evaluate the clustering model using the Davies-Bouldin Index, which measures the average similarity between clusters.
Choose the model with the lowest Davies-Bouldin Index as the optimal clustering model.
Visualization
Visualize the clusters using matplotlib.
Plot the Davies-Bouldin Index for different numbers of clusters to demonstrate the optimal number of clusters.
