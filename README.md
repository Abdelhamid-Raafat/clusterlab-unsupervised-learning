# ClusterLab — Unsupervised Learning Playground

A hands-on machine learning project exploring clustering algorithms and dimensionality reduction using Python and Scikit-learn.

## 📌 Project Overview

This project demonstrates key unsupervised learning techniques using synthetic datasets. It explores how different algorithms discover patterns, group data points, identify noise, and reduce dimensionality.

## Algorithms & Techniques

- **K-Means Clustering:** Groups data points into clusters using centroids.
- **Elbow Method:** Uses inertia to help determine a suitable number of clusters.
- **Silhouette Score:** Evaluates cluster separation and cohesion.
- **DBSCAN:** Identifies density-based clusters and detects noise points.
- **Gaussian Mixture Models (GMM):** Performs probabilistic clustering and estimates cluster membership probabilities.
- **Principal Component Analysis (PCA):** Reduces dimensionality while preserving as much variance as possible.

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/<your-username>/clusterlab-unsupervised-learning.git
cd clusterlab-unsupervised-learning
```

### 2. Install dependencies

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

Alternatively, if you have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

```bash
jupyter notebook
```

Open `clusterlab.ipynb` and run the cells sequentially.

## Learning Objectives

- Understand the fundamentals of unsupervised learning.
- Apply feature scaling before clustering.
- Visualize cluster assignments and centroids.
- Compare clustering methods and evaluation metrics.
- Understand hard cluster assignments versus probabilistic membership.
- Explore dimensionality reduction and explained variance using PCA.

## Datasets

The project uses synthetic datasets generated with Scikit-learn, including:

- `make_blobs` for K-Means clustering experiments.
- `make_moons` for exploring non-linear cluster structures.
- Synthetic high-dimensional data for PCA.

No external dataset download is required.
