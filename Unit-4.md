# Unit 4: Numerical Methods & Optimization – Formula Sheet

---

# 1. Bisection Method

### Condition for Existence of Root
```math
f(a)\times f(b)<0
```

### Midpoint Formula
```math
c=\frac{a+b}{2}
```

### Error After n Iterations
```math
\text{Error}\le \frac{b-a}{2^n}
```

### Interval Length After n Iterations
```math
L_n=\frac{L_0}{2^n}
```

---

# 2. Newton-Raphson Method

### Iteration Formula
```math
x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}
```

### Approximate Error
```math
E=|x_{n+1}-x_n|
```

### Derivative Formula
```math
f'(x)=\frac{d}{dx}[f(x)]
```

---

# 3. Gauss Elimination Method

### General System of Linear Equations
```math
AX=B
```

### Augmented Matrix
```math
[A|B]
```

### Elementary Row Operations

1. Row Interchange
```math
R_i \leftrightarrow R_j
```

2. Row Multiplication
```math
R_i \rightarrow kR_i
```

3. Row Replacement
```math
R_i \rightarrow R_i+kR_j
```

---

# 4. Gradient Descent

### Update Rule
```math
x_{\text{new}}=x_{\text{old}}-\alpha\nabla f(x)
```

where,

- \( \alpha \) = Learning Rate
- \( \nabla f(x) \) = Gradient of the function

### Gradient Formula
```math
\nabla f(x)=\frac{df}{dx}
```

### For \(f(x)=x^2\)
```math
\nabla f(x)=2x
```

### For \(f(x)=ax^2\)
```math
\nabla f(x)=2ax
```

---

# 5. Important Derivatives

### Power Rule
```math
\frac{d}{dx}(x^n)=nx^{n-1}
```

### Derivative of \(x^2\)
```math
\frac{d}{dx}(x^2)=2x
```

### Derivative of \(x^3\)
```math
\frac{d}{dx}(x^3)=3x^2
```

### Derivative of a Constant
```math
\frac{d}{dx}(c)=0
```

---

# Exam Shortcut Sheet

## Bisection Method
```math
c=\frac{a+b}{2}
```

```math
f(a)f(b)<0
```

---

## Newton-Raphson Method
```math
x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}
```

---

## Gradient Descent
```math
x_{\text{new}}=x_{\text{old}}-\alpha\nabla f(x)
```

---

## Common Derivatives
```math
\frac{d}{dx}(x^n)=nx^{n-1}
```

```math
\frac{d}{dx}(x^2)=2x
```

```math
\frac{d}{dx}(x^3)=3x^2
```

```math
\frac{d}{dx}(c)=0
```
