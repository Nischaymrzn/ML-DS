# 📘 Topic: Applying Calculus to Real Optimization Tasks

---

## ✅ Today's Learning Objectives Completed

- Explored how automatic differentiation works and why it’s essential in machine learning  
- Practiced implementing gradient descent to minimize loss functions  
- Revisited and reinforced key calculus concepts through hands-on application  

---

## 📝 Detailed Notes

### 🔹 Automatic Differentiation (AutoDiff)

- A method to **compute gradients efficiently and accurately** by breaking computations into atomic operations and applying the chain rule  
- Used extensively in ML frameworks like **TensorFlow**, **PyTorch**, and **JAX**  
- Key advantage: Combines the accuracy of symbolic differentiation with the speed of numerical methods  

---

### 🔹 Gradient Descent in Action

- Implemented a manual optimization loop:
  \[
  \theta \leftarrow \theta - \eta \cdot \nabla_\theta \mathcal{L}
  \]
  where \( \eta \) is the learning rate and \( \mathcal{L} \) is the loss function  
- Tuned learning rate and observed convergence patterns  

---

### 🔹 Revisited Key Concepts

- **Gradients**: Direction of steepest ascent; used in minimizing cost functions  
- **Hessians**: Captured second-order curvature for optimization insights  
- **Taylor Series**: Understood model approximation and gradient-based updates  
- Saw these ideas converge in a real optimization loop  

---

## 🔑 Key Takeaways

- Automatic differentiation makes complex model training scalable and efficient  
- Gradient descent remains the core algorithm for training many ML models  
- Reinforcing theory through code deepens both intuition and understanding  
