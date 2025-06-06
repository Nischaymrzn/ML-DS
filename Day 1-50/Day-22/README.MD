# 📘 Topic: Integration in Machine Learning Context

---

## ✅ Today's Learning Objectives Completed

- Understood how **definite integrals** are used in computing the **AUC-ROC**  
- Explored **numerical integration methods** for estimating area under curves  
- Connected integration to **probability, model evaluation**, and continuous functions in ML  

---

## 📝 Detailed Notes

### 🔹 AUC-ROC (Area Under the Curve)

- **ROC Curve** plots True Positive Rate (TPR) vs. False Positive Rate (FPR)
- **AUC** is the integral (area) under the ROC curve:  
  \[
  \text{AUC} = \int_{0}^{1} \text{TPR}(x) \, dx
  \]
- A higher AUC means better model separability
- In practice, AUC is estimated using numerical methods (like trapezoidal rule)

---

### 🔹 Numerical Integration

- Useful when analytic integration is hard or impossible
- **Trapezoidal Rule**: Approximates area using trapezoids  
  \[
  \int_a^b f(x)\,dx \approx \sum_{i=1}^{n} \frac{f(x_{i-1}) + f(x_i)}{2} \cdot (x_i - x_{i-1})
  \]
- **Simpson's Rule**: Uses parabolas for better approximation (more accurate but more complex)

---

### 🔹 Applications in Machine Learning

- **Probability & Expectation**:  
  Continuous probabilities (PDFs) often require integration to compute expectations, variances
- **Loss Functions & Optimization**:  
  Some loss formulations use integrals, especially in probabilistic models
- **Model Evaluation**:  
  AUC is an integral metric measuring overall model ranking quality

---

## 🔑 Key Takeaways

- Integration isn't just math—it's central to evaluating models and working with probabilities in ML
- Numerical integration bridges theory and real-world data when analytic solutions aren’t feasible
- Understanding AUC in ROC curves gives deeper insight into classifier performance
