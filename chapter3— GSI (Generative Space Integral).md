# Chapter 3 — GSI (Generative Space Integral)

## 1. Definition of GSI
The integral in OS Geometry is called  
**GSI (Generative Space Integral)**.

$$
\int_{\text{GSI}} f(x)\, d_{\text{OS}}x
\approx \sum_k f(x_k)\,\ell_{\text{OS}}(x_k)
$$

---

## 2. Essence of GSI
GSI measures the **total quantity in the generated space**, using:

- OS-generated trajectory  
- OS-generated differential $d_{\text{OS}}x$  
- observation function $f(x)$  

---

## 3. Difference from Ordinary Integrals

| Ordinary Integral | GSI |
|------------------|------|
| $dx$ is fixed | $d_{\text{OS}}x$ is generated |
| Space is fixed | Space is generated |
| Derivative is assumed | Derivative is generated |
| Analytical | Generative |

---

## 4. Observation Function $f(x)$
$f(x)$ determines **how the generated world is observed**.

Examples:  
- $f(x)=1$ → length of trajectory  
- $f(x)=x^2$ → emphasizes distant regions  
- $f(x)=e^x$ → emphasizes right-side regions
