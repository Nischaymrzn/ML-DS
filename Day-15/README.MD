# 📘 Topic: Optimization with Gradient Descent and Least Squares

---

## ✅ Today's Learning Objectives Completed

- Learned to apply gradient descent for functions with two variables to locate minima  
- Studied the Least Squares method to minimize errors between observed data points and model predictions  
- Explored how Least Squares handles multiple observations for improved model fitting  

---

## 📝 Detailed Notes

### 🔹 Optimization in Two Variables

- Gradient descent extends to multivariable functions by updating each parameter simultaneously  
- Uses the gradient vector consisting of partial derivatives with respect to each variable  
- Iterative updates continue until convergence to a minimum  

---

### 🔹 Least Squares Method

- Objective is to minimize the sum of squared differences between observed and predicted values  
- Provides a way to fit models that best explain the data by reducing overall error  

---

### 🔹 Multiple Observations in Least Squares

- Aggregates errors from multiple data points to find optimal parameters  
- Improves model accuracy by considering the full dataset during fitting  

---

## 🔑 Key Takeaways

- Gradient descent in multiple variables requires vectorized updates for efficiency  
- Least squares is a fundamental approach to error minimization in regression  
- Using multiple observations makes model fitting more robust and reliable  

---

## 💡 Practical Implementation Tips

- Use vectorized operations to compute gradients efficiently in multivariate cases  
- Ensure data quality and outlier handling to get good least squares fits  
- Monitor convergence during gradient descent to avoid overfitting or underfitting  
