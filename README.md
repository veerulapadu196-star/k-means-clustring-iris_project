# K-Means Clustering on Iris Dataset

## Overview
This project applies the **K-Means clustering algorithm** (unsupervised learning) to the classic **Iris dataset** to group flower samples into clusters based on their physical measurements — without using the actual species labels during training.

## Dataset
- **Source:** `sklearn.datasets.load_iris`
- **Features:** Sepal Length, Sepal Width, Petal Length, Petal Width
- **Samples:** 150 (50 each of Setosa, Versicolor, Virginica)

## Approach
1. Loaded the Iris dataset using scikit-learn.
2. Converted features into a Pandas DataFrame for exploration.
3. Applied **K-Means** with `n_clusters=3` (matching the 3 known species).
4. Predicted cluster labels using `fit_predict()`.
5. Visualized the clusters with a scatter plot (Sepal Length vs Sepal Width), color-coded by cluster assignment.

## Tech Stack
- Python
- scikit-learn (`KMeans`, `load_iris`)
- Pandas
- Matplotlib

## Output
A scatter plot showing how K-Means groups the flowers into 3 clusters purely from their measurements — demonstrating how unsupervised learning can uncover natural groupings in data.

## Key Takeaway
K-Means successfully identifies distinct clusters in the Iris dataset that closely align with the actual species groups, showcasing the power of clustering for pattern discovery in unlabeled data.
