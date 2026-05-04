# Chapter 2 — MDAD (OS-Derivative)

## 1. Definition of MDAD
MDAD is the **difference along the OS-generated trajectory**.

$$
\text{MDAD}_f(x_k) = f(x_{k+1}) - f(x_k)
$$

Unlike ordinary derivatives,  
it measures change **along $d_{\text{OS}}x$**.

---

## 2. Properties
- Depends on OS-dir / OS-scale  
- Changes when the trajectory changes  
- Derivatives become *results of generation*  

---

## 3. Example
For gradient-following $G$,  
MDAD approximates directional differences along the gradient.
