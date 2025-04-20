# Day 6 – Singular Value Decomposition (SVD)
**Topic:** Singular Value Decomposition (SVD)

---

## 📘 SVD Theory

- **Definition**: Singular Value Decomposition (SVD) is a matrix factorization technique that breaks a matrix **A** into three components:  
  **A = UΣVᵀ**,  
  where:
  - **U** contains the left singular vectors,
  - **Σ** is a diagonal matrix with singular values,
  - **Vᵀ** contains the right singular vectors.
- **Purpose**: Simplifies matrix computations and reveals intrinsic properties of the data such as rank and range.

---

## 🧠 SVD in Machine Learning

- **Dimensionality Reduction**: Reduces the number of features by retaining the most significant singular values.
- **Feature Extraction**: Helps identify the most informative features for modeling.
- **Noise Filtering**: Eliminates low-variance components that often represent noise in the dataset.
- **Efficiency**: Enables faster computation and model training by working with compressed representations.

---

## 🔄 SVD & PCA

- **Connection**: PCA uses SVD to compute the principal components of a dataset.
- **Goal of PCA**: Transform the original dataset into a set of linearly uncorrelated components that capture the most variance.
- **How SVD Helps**:
  - Identifies the directions (principal axes) that best represent the data.
  - Projects the data onto a lower-dimensional space while retaining essential structure.

---
