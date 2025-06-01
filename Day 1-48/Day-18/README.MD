# 📘 Topic: Constrained Optimization with Lagrange Multipliers

---

## ✅ Today's Learning Objectives Completed

- Learned how Lagrange Multipliers help optimize functions with constraints  
- Understood the impact of constraints on optimization problems  
- Saw how gradient-based strategies adapt under constraints  

---

## 📝 Detailed Notes

### 🔹 Lagrange Multipliers

- Used to find **local maxima/minima** of a function \( f(x, y, \dots) \) subject to a constraint \( g(x, y, \dots) = 0 \)  
- Form the **Lagrangian**:  
  \[
  \mathcal{L}(x, y, \lambda) = f(x, y) - \lambda (g(x, y) - c)
  \]  
- Set gradients to zero:  
  \[
  \nabla f = \lambda \nabla g
  \]  
  along with the constraint \( g(x, y) = c \)

---

### 🔹 Constrained Optimization

- Unlike unconstrained optimization, the solution must lie on a constraint surface  
- The gradients of the objective function and the constraint must be **parallel** at the optimal point  
- Ensures no movement possible that improves \( f \) without violating the constraint

---

### 🔹 Gradient Strategy Adaptation

- In constrained settings, the search direction must be **tangent to the constraint surface**  
- Lagrange multipliers provide a systematic way to adjust direction using gradient information from both objective and constraint functions

---

## 🔑 Key Takeaways

- Lagrange Multipliers elegantly solve constrained optimization problems without eliminating variables  
- They reveal the **trade-off** between improving the objective function and satisfying the constraint  
- The method is widely used in economics, physics, machine learning (e.g., SVMs), and engineering  

---

## 💡 Practical Notes

- Can extend to multiple constraints using multiple multipliers  
- Nonlinear constraints may require **Karush-Kuhn-Tucker (KKT)** conditions (a generalization of Lagrange multipliers)
