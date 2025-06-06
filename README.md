# AIML-Task8
# Mall Customers K-Means Clustering

This project uses K-Means clustering to segment customers by annual income and spending score from the Mall Customers dataset.

## Motivation

Customer segmentation assists companies in adapting marketing efforts and enhancing customer satisfaction by recognizing individual groups with similar patterns of behavior.

## Method and Results

- Data from `Mall_Customers.csv` is loaded and features selected for cluster analysis.
- PCA is applied to plot data in 2D.
- The Elbow Method identifies the number of optimal clusters.
- K-Means clustering segments customers into 5 groups.
- Clusters are visualized using color coding for PCA components.
- Silhouette Score computes the quality of the clusters.

## Usage

1. Put `Mall_Customers.csv` in your working directory or Google Colab `/content/`.
2. Execute the Python script to run clustering and display results.
3. Inspect plots and Silhouette Score output.

## Requirements

- pandas
- scikit-learn
- matplotlib


