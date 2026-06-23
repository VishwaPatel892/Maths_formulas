# 📘 Unit 3: Linear Algebra – Formula Sheet

---

# 1. Dot Product

For vectors:

- **a = (x₁, y₁)**
- **b = (x₂, y₂)**

### Formula
```math
a \cdot b = x_1x_2 + y_1y_2
```

For 3D vectors:

```math
a \cdot b = x_1x_2 + y_1y_2 + z_1z_2
```

---

# 2. Magnitude (Norm) of a Vector

For a 2D vector:

```math
|(x,y)| = \sqrt{x^2+y^2}
```

For a 3D vector:

```math
|(x,y,z)| = \sqrt{x^2+y^2+z^2}
```

---

# 3. Unit Vector

If **v ≠ 0**, then the unit vector in the direction of **v** is:

```math
\hat{v}=\frac{v}{|v|}
```

---

# 4. Angle Between Two Vectors

### Formula

```math
\cos \theta = \frac{a \cdot b}{|a||b|}
```

Therefore,

```math
\theta = \cos^{-1}\left(\frac{a \cdot b}{|a||b|}\right)
```

---

# 5. Orthogonal Vectors

Two vectors are orthogonal if:

```math
a \cdot b = 0
```

---

# 6. Projection of Vector a onto Vector b

### Formula

```math
\text{proj}_b(a)=\frac{a \cdot b}{b \cdot b}\,b
```

---

# 7. Linear Independence

Vectors

```math
v_1,v_2,\dots,v_n
```

are linearly independent if

```math
a_1v_1+a_2v_2+\cdots+a_nv_n=0
```

has only the trivial solution:

```math
a_1=a_2=\cdots=a_n=0
```

---

# 8. Basis

A set of vectors is called a **Basis** if:

- The vectors are linearly independent.
- The vectors span the vector space.

---

# 9. Dimension

**Dimension = Number of vectors in a basis**

Examples:

```math
\dim(R^2)=2
```

```math
\dim(R^3)=3
```

---

# 10. Characteristic Equation

For a square matrix **A**:

```math
|A-\lambda I|=0
```

where

- **A** = Matrix
- **I** = Identity Matrix
- **λ** = Eigenvalue

---

# 11. Eigenvalue Equation

```math
Av=\lambda v
```

where

- **A** = Matrix
- **v** = Eigenvector
- **λ** = Eigenvalue

---

# 12. Diagonal Matrix

A matrix is diagonal if all off-diagonal elements are zero.

Example:

```math
\begin{bmatrix}
2 & 0 \\
0 & 5
\end{bmatrix}
```

---

# 13. Positive Definite Matrix

A matrix is positive definite if all its eigenvalues are positive:

```math
\lambda_1>0,\quad \lambda_2>0,\quad \dots,\quad \lambda_n>0
```

---

# ⭐ Most Important Formulas for Exams

### Dot Product

```math
a \cdot b = x_1x_2 + y_1y_2
```

### Magnitude

```math
|v|=\sqrt{x^2+y^2+z^2}
```

### Unit Vector

```math
\hat{v}=\frac{v}{|v|}
```

### Angle Between Two Vectors

```math
\cos \theta=\frac{a \cdot b}{|a||b|}
```

### Projection

```math
\text{proj}_b(a)=\frac{a \cdot b}{b \cdot b}b
```

### Characteristic Equation

```math
|A-\lambda I|=0
```

### Eigenvalue Equation

```math
Av=\lambda v
```

---

# 🎯 Exam Tip

Remember these keywords:

- Dot Product → Multiplication + Addition
- Orthogonal → Dot Product = 0
- Unit Vector → Divide by Magnitude
- Projection → Dot Product over Magnitude Squared
- Eigenvalue → Solve `|A−λI| = 0`
- Positive Definite → All Eigenvalues > 0
