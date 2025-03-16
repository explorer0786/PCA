# Principal Component Analysis (PCA) in Machine Learning

## Overview
Principal Component Analysis (PCA) is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space while preserving the most important information. It achieves this by identifying **principal components**, which are orthogonal axes that capture the most variance in the data.

## Key Concepts

- **Dimensionality Reduction**: PCA reduces the number of variables (features) in a dataset, making it easier to analyze, visualize, and model.
- **Principal Components**: These are new, uncorrelated variables that are linear combinations of the original variables.
- **Variance**: 
  - The first principal component captures the most variance in the data.
  - The second captures the next most, and so on.
- **Applications**: PCA is used in various machine learning tasks, including:
  - Data preprocessing
  - Feature extraction
  - Visualization
- **Unsupervised Learning**: PCA is an **unsupervised learning** technique, meaning it doesn't require labeled data or a target variable.

## How PCA Works

1. **Standardization**: The data is standardized (or centered) to ensure each feature contributes equally.
2. **Covariance Matrix Calculation**: Compute the covariance matrix to understand relationships between variables.
3. **Eigenvectors & Eigenvalues**: Identify eigenvectors and eigenvalues of the covariance matrix.
4. **Principal Component Selection**: Choose the eigenvectors corresponding to the largest eigenvalues.
5. **Projection**: Project the original data onto the principal components to obtain a reduced representation.

---
