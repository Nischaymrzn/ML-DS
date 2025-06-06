# Topic: K-Means Clustering — Model Evaluation Techniques

## Today's Learning Objectives Completed

- Explored methods to evaluate and choose the optimal number of clusters  
- Learned the Elbow Method to analyze distortion scores  
- Understood the Silhouette Score as a measure of clustering quality  

---

## Detailed Notes

### Elbow Method

- Plots the distortion (sum of squared distances from points to their cluster centroids) against the number of clusters *k*  
- The "elbow" point in the plot indicates a good balance between cluster compactness and number of clusters  
- Helps decide the optimal *k* by locating where increasing clusters yields diminishing returns  

### Silhouette Score

- Measures how similar a point is to its own cluster compared to other clusters  
- Score ranges from -1 to 1:  
  - Close to 1 means the point is well matched to its cluster  
  - Around 0 means the point lies between clusters  
  - Negative values indicate possible misclassification  
- Provides an overall metric for clustering quality beyond just distortion  

---

## Key Takeaways

- Choosing the right number of clusters is crucial for effective K-Means clustering  
- The Elbow Method is a visual heuristic based on within-cluster variance  
- Silhouette Score offers a more quantitative evaluation of cluster cohesion and separation  
