# 📘 Topic: Polynomial Regression and Model Evaluation

---

## ✅ Today's Learning Objectives Completed

- Understanding how polynomial regression extends linear regression for non-linear data  
- Learning evaluation metrics: MAE, MSE, and RMSE  
- Comparing linear and polynomial models based on fit and complexity  

---

## 📝 Detailed Notes

### 🔹 Polynomial Regression

- Extends linear regression by adding polynomial terms of features  
- Captures non-linear relationships between features and target  
- Model form:  
  fw,b(x) = w₀ + w₁x + w₂x² + ... + wₙxⁿ  

---

### 🔹 Model Evaluation Metrics

- **MAE (Mean Absolute Error)**: Average absolute difference between predicted and actual values  
- **MSE (Mean Squared Error)**: Average squared difference, penalizes larger errors more  
- **RMSE (Root Mean Squared Error)**: Square root of MSE, interpretable in original units  

---

### 🔹 Model Comparison

- Linear regression: simpler, less flexible, may underfit non-linear data  
- Polynomial regression: more flexible, can fit complex patterns but risks overfitting  
- Evaluation metrics help quantify performance and select appropriate model complexity  

---

## 🔑 Key Takeaways

- Polynomial regression enables modeling of curved relationships  
- Choosing the right degree of polynomial is crucial to avoid overfitting  
- Use evaluation metrics to compare and validate model performance  

---

## 💡 Practical Implementation Tips

- Start with lower-degree polynomials and increase complexity gradually  
- Always evaluate on validation/test data to check for overfitting  
- Use regularization if polynomial degree is high  
- Visualize model fit to better understand behavior  
