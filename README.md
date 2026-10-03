# Dimensionality Reduction & Unsupervised Clustering

## Project Overview

This project explores high-dimensional data using **Principal Component Analysis (PCA)** and unsupervised clustering algorithms. The goal is to reduce the dimensionality of numerical data, discover hidden patterns, and compare different clustering techniques.

The project uses the Iris dataset to demonstrate dimensionality reduction and clustering with Python.

## Objectives

* Standardize numerical features before analysis.
* Apply PCA to reduce the dimensionality of the dataset.
* Visualize explained variance using a scree plot.
* Determine the optimal number of clusters using the Elbow Method and Silhouette Score.
* Apply K-Means, DBSCAN, and Hierarchical Clustering.
* Visualize clusters using 2D and 3D PCA projections.
* Compare clustering performance and interpret the results.

## Technologies Used

* Python
* Jupyter Notebook
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Plotly
* SciPy

## Dataset

**Dataset:** Iris Dataset

The Iris dataset contains 150 samples of iris flowers, with four numerical features:

* Sepal length
* Sepal width
* Petal length
* Petal width

The species labels are used for post-clustering interpretation and visualization, not to train the unsupervised clustering algorithms.

## Algorithms Implemented

### 1. Principal Component Analysis (PCA)

PCA transforms the original numerical features into principal components. Explained variance and cumulative explained variance are examined to understand how much information is retained after dimensionality reduction.

### 2. K-Means Clustering

K-Means groups data points into clusters based on their distances from cluster centroids.

* Elbow Method to examine within-cluster sum of squares.
* Silhouette Score to evaluate cluster separation.
* 2D and 3D visualizations of the resulting clusters.

### 3. DBSCAN Clustering

DBSCAN identifies clusters based on point density.

* Uses `eps` and `min_samples` parameters.
* Identifies noise points and outliers.
* Visualizes cluster assignments in PCA space.

### 4. Hierarchical Clustering

Agglomerative Hierarchical Clustering builds clusters by progressively merging similar data points or groups. Its results are compared with those of K-Means and DBSCAN.

## Project Workflow

1. Load and explore the dataset.
2. Standardize the numerical features.
3. Apply PCA and analyze explained variance.
4. Visualize the reduced data in 2D and 3D.
5. Determine a suitable number of clusters for K-Means.
6. Apply DBSCAN and identify noise points.
7. Apply Hierarchical Clustering.
8. Compare clustering results and interpret the findings.

## Key Findings

* PCA provides a lower-dimensional representation of the original dataset.
* The scree plot and cumulative explained variance help determine how many principal components to retain.
* The Elbow Method and Silhouette Score help assess suitable K-Means cluster counts.
* DBSCAN can identify noise points and may produce different results depending on its parameters.
* Hierarchical Clustering provides another way to explore the structure of the dataset.
* Clustering algorithms may produce different groupings because they use different approaches to define clusters.

The notebook contains the actual visualizations, evaluation metrics, and detailed observations from the analysis.

## How to Run the Project

1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook or VS Code.
3. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn plotly scipy nbformat ipython
```

4. Run the notebook cells from beginning to end.

## Project File

* `Dimensionality_Reduction_Unsupervised_Clustering.ipynb` — Complete implementation, visualizations, evaluation metrics, and conclusions.

## Conclusion

This project demonstrates how PCA and unsupervised clustering algorithms can be used to explore high-dimensional data, visualize hidden patterns, and compare different approaches to clustering.

---

**Project Type:** Data Science / Machine Learning
**Topics:** Dimensionality Reduction, PCA, Unsupervised Learning, Clustering, Data Visualization
