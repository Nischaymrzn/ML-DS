# 📘 Topic: Newton’s Method and Second-Order Optimization

---

## ✅ Today's Learning Objectives Completed

- Learned how Newton’s Method uses derivatives to find roots of functions  
- Understood how Newton-Raphson applies to optimization using gradient and curvature  
- Realized how second-order information leads to faster and more efficient optimization  

---

## 📝 Detailed Notes

### 🔹 Newton’s Method

- An iterative method to find the roots of a real-valued function \( f(x) = 0 \)  
- Update rule:  
  \[
  x_{\text{new}} = x - \frac{f(x)}{f'(x)}
  \]

---

### 🔹 Newton-Raphson for Optimization

- Adapted to find **minima** by applying Newton’s Method to \( f'(x) = 0 \)  
- Incorporates second derivative (Hessian) to improve step direction:  
  \[
  x_{\text{new}} = x - \frac{f'(x)}{f''(x)}
  \]  
- For multivariable functions:  
  \[
  \mathbf{x}_{\text{new}} = \mathbf{x} - H^{-1} \nabla f(\mathbf{x})
  \]

---

### 🔹 Key Insight

- Gradient Descent uses only **first-order** (slope) information  
- Newton’s Method leverages **second-order** (curvature) for faster convergence  
- Especially useful near minima where curvature helps direct larger, more accurate steps  

---

## 🔑 Key Takeaways

- Newton’s Method can converge much faster than gradient descent when second derivatives are available and well-behaved  
- Second-order methods are more computationally intensive but powerful in fine-tuning optimization  
- Care must be taken when the Hessian is non-invertible or too complex  

---

## 💡 Practical Notes

- Use **quasi-Newton methods** like BFGS if computing full Hessian is expensive  
- Newton's Method can diverge if the starting point is far from the minimum or the curvature is poorly estimated  
