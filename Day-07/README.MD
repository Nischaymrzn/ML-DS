# Day 7 – Linear Discriminant Analysis (LDA)
**Topic:** Linear Discriminant Analysis (LDA)

---

## 📘 LDA Theory

- **Definition**: Linear Discriminant Analysis (LDA) is a dimensionality reduction technique that finds a linear combination of features to best separate two or more classes.
- **Goal**: Maximize class separability while minimizing variation within each class.
- **Approach**: Projects high-dimensional data onto a lower-dimensional space using eigen decomposition of scatter matrices.

---

## 🔍 LDA vs PCA

| Aspect | LDA | PCA |
|-------|-----|-----|
| Type | Supervised | Unsupervised |
| Objective | Maximize class separability | Maximize overall variance |
| Uses class labels? | Yes | No |
| Output | Lower dimensions with preserved class-discriminatory information | Lower dimensions with preserved overall variance |

- **Insight**: LDA is ideal for classification tasks, whereas PCA is used more broadly for general data compression.

---

## 📈 LDA for Model Performance

- **Feature Reduction**: Simplifies the model by reducing input features without losing critical class information.
- **Improved Accuracy**: Preserves class structure, which often leads to better classification performance.
- **Usage**: Widely used in pattern recognition, bioinformatics, and text classification tasks.

---
