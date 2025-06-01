# 📘 Matrices Revision Notes

## 📌 Matrix Basics & Operations

- **Matrix**: A rectangular array of numbers arranged in rows and columns. It is used to represent data and solve linear equations.
- **Matrix Operations**:
  - **Addition/Subtraction**: Performed element-wise, only for matrices of the same dimensions.
  - **Scalar Multiplication**: Multiply every element of the matrix by a scalar value.
  - **Matrix Multiplication**: Multiply matrices where the number of columns of the first matrix matches the number of rows in the second matrix.
  - **Transpose**: Swap the rows and columns of a matrix.
  - **Inverse**: The inverse of a matrix \(A\) is denoted as \(A^{-1}\) such that \(A \times A^{-1} = I\), where \(I\) is the identity matrix.

---

## Row Echelon Form & Gaussian Elimination

- **Row Echelon Form (REF)**: A matrix is in REF if:
  - All rows with non-zero entries are above rows of all zeros.
  - The leading entry (first non-zero element) in each row is to the right of the leading entry of the row above it.
  - All entries below a leading entry are zeros.
  
- **Gaussian Elimination**: A process for solving systems of linear equations:
  - Convert the augmented matrix to REF using row operations.
  - Use back-substitution to find the solution.

---

## Span, Rank & Basis

- **Span**: The set of all possible linear combinations of a given set of vectors. It defines the space spanned by those vectors.
- **Rank**: The number of linearly independent rows (or columns) in a matrix. It determines the dimension of the column space and row space.
- **Basis**: A set of linearly independent vectors that span a vector space. Every vector in that space can be written as a linear combination of the basis vectors.

---

## Determinants & Linear Transformations

- **Determinants**: A scalar value computed from a square matrix that provides important properties, such as:
  - **Invertibility**: A matrix is invertible if its determinant is non-zero.
  - **Volume Scaling**: The absolute value of the determinant represents the scaling factor of areas or volumes under the matrix transformation.
  
- **Linear Transformations**: Functions that map vectors from one vector space to another, while preserving vector addition and scalar multiplication. These transformations are often represented using matrices and can be used to rotate, scale, or shear objects in geometry.

---
