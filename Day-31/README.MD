# 📘 Topic: ElasticNet Regression and Model Comparison

---

## ✅ Today's Learning Objectives Completed

- Understanding how ElasticNet combines L1 (Lasso) and L2 (Ridge) penalties  
- Implementing ElasticNet regression  
- Comparing ElasticNet with Ridge and Lasso regression models  
- Evaluating models using R² Score, MSE, and RMSE  

---

## 📝 Detailed Notes

### 🔹 ElasticNet Regression

- Combines L1 and L2 regularization penalties in a single model  
- Addresses limitations of Ridge and Lasso, especially with correlated features (multicollinearity)  
- Controlled by two hyperparameters: alpha (regularization strength) and l1_ratio (balance between L1 and L2)  

---

### 🔹 Model Evaluation Metrics

- **R² Score:** Measures proportion of variance explained by the model  
- **Mean Squared Error (MSE):** Average squared difference between predicted and actual values  
- **Root Mean Squared Error (RMSE):** Square root of MSE, interpretable in original units  

---

### 🔹 Model Comparison

- ElasticNet provides a flexible regularization approach balancing sparsity and coefficient shrinkage  
- Useful for datasets where predictors are correlated  
- Evaluation metrics guide selection of the best model for given data  

---

## 🔑 Key Takeaways

- ElasticNet is a hybrid regularization technique combining L1 and L2 penalties  
- It effectively handles multicollinearity and feature selection simultaneously  
- Comparing models using R², MSE, and RMSE helps identify the best fit  

---

## 💡 Practical Implementation Tips

- Tune both alpha and l1_ratio hyperparameters via cross-validation  
- Use ElasticNet when features are correlated and sparse models are desired  
- Always compare models on validation/test data using multiple metrics  
- Visualize residuals and prediction errors for deeper insight  
