---
title: Projections & Least Squares

---

# 📘 Practice Sheet  
## Lecture: Projections & Least Squares

## 🧠 SECTION A: Conceptual Questions (10 MCQs)

### Q1. (Easy | MCQ)
The projection of a vector **v** onto a non-zero vector **u** is:
A. A scalar multiple of **v**  
B. Always orthogonal to **u**  
C. A scalar multiple of **u**  
D. Independent of **u**

---

### Q2. (Easy | MCQ)
If **p** is the projection of **v** onto a subspace **W**, then **v − p** is:
A. In **W**  
B. Orthogonal to **W**  
C. Parallel to **W**  
D. Equal to zero

---

### Q3. (Medium | MCQ)
Which condition guarantees a **unique** projection of **v** onto a subspace **W**?
A. **W** is finite  
B. **W** is a vector space  
C. **W** is a subspace  
D. **W** contains **v**

---

### Q4. (Medium | MCQ)
Which condition defines a projection matrix **P**?
A. \( P^2 = I \)  
B. \( P^T = -P \)  
C. \( P^2 = P \)  
D. \( \det(P) = 1 \)

---

### Q5. (Medium | MCQ)
If **P** is a projection matrix, then:
A. **P** is always invertible  
B. **P = P^{-1}**  
C. **P = P^T** (sometimes)  
D. **P** must be diagonal

---

### Q6. (Medium | MCQ)
The normal equations arise when:
A. Solving \( Ax = b \) exactly  
B. Minimizing \( \|Ax - b\| \)  
C. Computing eigenvalues  
D. Orthogonalizing vectors

---

### Q7. (Hard | MCQ)
Geometrically, the least squares solution \( \hat{x} \) satisfies:
A. \( A\hat{x} = b \)  
B. \( b - A\hat{x} \perp \text{Null}(A) \)  
C. \( b - A\hat{x} \perp \text{Col}(A) \)  
D. \( A\hat{x} \perp b \)

---

### Q8. (Medium | MCQ)
Which matrix projects vectors onto **Col(A)**?
A. \( A^TA \)  
B. \( AA^T \)  
C. \( A(A^TA)^{-1}A^T \)  
D. \( (A^TA)^{-1} \)

---

### Q9. (Hard | MCQ)
If columns of **A** are linearly dependent, then:
A. Least squares has no solution  
B. Normal equations are invalid  
C. Multiple least squares solutions may exist  
D. Projection does not exist

---

### Q10. (Easy | MCQ)
Least squares regression is needed when:
A. \( Ax = b \) has infinitely many solutions  
B. \( Ax = b \) has no solution  
C. \( A \) is square  
D. \( A \) is invertible

---

## 🔢 SECTION B: Numerical / Problem Solving (20 Questions)

### 🔹 Projection onto a Line

### Q11. (Easy | MCQ)
Project **v = (2, 2)** onto **u = (1, 0)**.
A. (2, 0)  
B. (1, 1)  
C. (0, 2)  
D. (1, 0)

---

### Q12. (Medium | Manual Input)
Find the projection of  
\( v = (3, 4) \)  
onto the line spanned by  
\( u = (1, 2) \).

---

### Q13. (Hard | MCQ)
Which vector is the projection of **v = (1, 2, 3)** onto **u = (1, 1, 1)**?
A. (1,1,1)  
B. (2,2,2)  
C. \( \left(\frac{6}{3},\frac{6}{3},\frac{6}{3}\right) \)  
D. \( \left(\frac{6}{3},\frac{6}{3},\frac{6}{3}\right) \)

---

### 🔹 Projection onto a Subspace

### Q14. (Medium | MCQ)
Project **v = (1,2,1)** onto  
\( W = \text{span}\{(1,0,0),(0,1,0)\} \)
A. (1,2,0)  
B. (0,0,1)  
C. (1,0,1)  
D. (0,2,1)

---

### Q15. (Medium | Manual Input)
Find the projection of  
\( v = (2,1,3) \)  
onto  
\( W = \text{span}\{(1,1,0),(0,1,1)\} \).

---

### Q16. (Hard | MCQ)
If **W** is spanned by orthonormal vectors \( q_1, q_2 \), then projection of **v** onto **W** equals:
A. \( q_1 + q_2 \)  
B. \( (v·q_1)q_1 + (v·q_2)q_2 \)  
C. \( (v·q_1 + v·q_2)(q_1 + q_2) \)  
D. \( v - q_1 - q_2 \)

---

### 🔹 Projection Matrix

### Q17. (Easy | MCQ)
Which of the following is always true for a projection matrix **P**?
A. \( P^T = P \)  
B. \( P^2 = P \)  
C. \( \det(P) = 1 \)  
D. \( P^{-1} \) exists

---

### Q18. (Medium | Manual Input)
Find the projection matrix onto the x-axis in \( \mathbb{R}^2 \).

---

### Q19. (Hard | MCQ)
Which matrix projects onto **span{(1,1)}**?
A. \( \begin{bmatrix}1&0\\0&1\end{bmatrix} \)  
B. \( \frac12\begin{bmatrix}1&1\\1&1\end{bmatrix} \)  
C. \( \begin{bmatrix}1&1\\0&0\end{bmatrix} \)  
D. \( \begin{bmatrix}0&0\\1&1\end{bmatrix} \)

---

### 🔹 Normal Equation & Least Squares

### Q20. (Medium | MCQ)
The normal equation is:
A. \( Ax = b \)  
B. \( A^TAx = b \)  
C. \( A^TAx = A^Tb \)  
D. \( AA^Tx = b \)

---

### Q21. (Medium | Manual Input)
Solve the normal equation for:
\( A = \begin{bmatrix}1\\1\end{bmatrix},\quad b = \begin{bmatrix}1\\2\end{bmatrix} \).

---

### Q22. (Hard | MCQ)
What does the least squares solution minimize?
A. \( \|Ax\| \)  
B. \( \|x\| \)  
C. \( \|Ax - b\|^2 \)  
D. \( \|A^Tx - b\| \)

---

### Q23. (Medium | MCQ)
In least squares regression, the predicted vector \( A\hat{x} \) lies in:
A. \( \mathbb{R}^n \)  
B. Null(A)  
C. Col(A)  
D. Row(A)

---

### Q24. (Hard | Manual Input)
Given data points  
\( (1,1),(2,2),(3,2) \),  
find the best fit line \( y = mx \) using least squares.

---

### Q25. (Easy | MCQ)
Least squares regression gives:
A. Exact fit always  
B. Best approximate solution  
C. Maximum error solution  
D. Orthogonal matrix

---

### Q26. (Medium | Manual Input)
Explain **in one sentence** why \( A^TAx = A^Tb \) represents orthogonality.

---

### Q27. (Hard | MCQ)
If \( b \in \text{Col}(A) \), then least squares solution:
A. Does not exist  
B. Is approximate  
C. Is exact  
D. Is non-unique

---

### Q28. (Medium | MCQ)
Residual vector \( r = b - A\hat{x} \) is orthogonal to:
A. \( b \)  
B. \( A\hat{x} \)  
C. Columns of \( A \)  
D. \( \hat{x} \)

---

### Q29. (Hard | Manual Input)
State the geometric meaning of least squares in \( \mathbb{R}^2 \).

---

### Q30. (Easy | MCQ)
Least squares is essentially a problem of:
A. Differentiation  
B. Eigenvalues  
C. Projection  
D. Matrix inversion

# 📘 Solutions — Projections & Least Squares

---

## 🧠 SECTION A: Conceptual Questions — Solutions

### Q1.
The projection of a vector **v** onto a non-zero vector **u** is always a scalar multiple of **u**.
**Answer:** C

---

### Q2.
For any projection:
v = p + (v − p), where (v − p) is orthogonal to the subspace.
**Answer:** B

---

### Q3.
A unique projection exists only when the target set is a **subspace**.
**Answer:** C

---

### Q4.
Projection matrices satisfy idempotence:
P² = P
**Answer:** C

---

### Q5.
A projection matrix is symmetric only in standard orthogonal projections.
**Answer:** C

---

### Q6.
Normal equations arise from minimizing the error norm:
‖Ax − b‖
**Answer:** B

---

### Q7.
Least squares residual satisfies:
b − A x̂ ⟂ Col(A)
**Answer:** C

---

### Q8.
Projection matrix onto column space is:
P = A(AᵀA)⁻¹Aᵀ
**Answer:** C

---

### Q9.
If columns of A are dependent, multiple least-squares solutions may exist.
**Answer:** C

---

### Q10.
Least squares is used when Ax = b has no exact solution.
**Answer:** B

---

## 🔢 SECTION B: Numerical / Problem Solving — Solutions

---

## 🔹 Projection onto a Line

### Q11.
v = (2, 2), u = (1, 0)

projᵤ(v) = (v·u / u·u) u  
= (2 / 1)(1,0)  
= (2,0)

**Answer:** A

---

### Q12.
v = (3,4), u = (1,2)

v·u = 3 + 8 = 11  
u·u = 1 + 4 = 5  

projᵤ(v) = (11/5)(1,2)  
= (11/5, 22/5)

---

### Q13.
v = (1,2,3), u = (1,1,1)

v·u = 6  
u·u = 3  

projᵤ(v) = (6/3)(1,1,1)  
= (2,2,2)

**Answer:** B

---

## 🔹 Projection onto a Subspace

### Q14.
Projection onto xy-plane removes z-component:

proj(v) = (1,2,0)

**Answer:** A

---

### Q15.
Basis vectors:
u₁ = (1,1,0), u₂ = (0,1,1)

Matrix:
A = [[1,0],
     [1,1],
     [0,1]]

Compute:
AᵀA = [[2,1],
        [1,2]]

Aᵀv = [3,4]

Solve:
[2 1][x₁] = [3]
[1 2][x₂]   [4]

x₁ = 1, x₂ = 3/2

Projection:
p = x₁u₁ + x₂u₂  
= (1,1,0) + (0,3/2,3/2)  
= (1, 5/2, 3/2)

---

### Q16.
For orthonormal basis:
proj(v) = Σ (v·qᵢ)qᵢ

**Answer:** B

---

## 🔹 Projection Matrix

### Q17.
Projection matrices satisfy:
P² = P

**Answer:** B

---

### Q18.
Projection onto x-axis in ℝ²:

P = [[1,0],
     [0,0]]

---

### Q19.
u = (1,1)

P = (uuᵀ)/(uᵀu)  
= (1/2)[[1,1],
        [1,1]]

**Answer:** B

---

## 🔹 Normal Equation & Least Squares

### Q20.
Normal equation:
AᵀAx = Aᵀb

**Answer:** C

---

### Q21.
A = [1,1]ᵀ, b = [1,2]ᵀ

AᵀA = 2  
Aᵀb = 3  

x = 3/2

---

### Q22.
Least squares minimizes:
‖Ax − b‖²

**Answer:** C

---

### Q23.
Predicted vector A x̂ lies in Col(A).
**Answer:** C

---

### Q24.
Data: (1,1), (2,2), (3,2)

Model: y = mx

A = [1,2,3]ᵀ  
b = [1,2,2]ᵀ  

AᵀA = 14  
Aᵀb = 11  

m = 11/14

---

### Q25.
Least squares gives best approximate solution.
**Answer:** B

---

### Q26.
Normal equation ensures the residual is orthogonal to Col(A).

---

### Q27.
If b ∈ Col(A), exact solution exists.
**Answer:** C

---

### Q28.
Residual r is orthogonal to columns of A.
**Answer:** C

---

### Q29.
Least squares finds the closest point in a subspace to a given vector.

---

### Q30.
Least squares is fundamentally a projection problem.
**Answer:** C

---

## ✅ FINAL ANSWER KEY

1:C  2:B  3:C  4:C  5:C  
6:B  7:C  8:C  9:C 10:B  
11:A 12:— 13:B 14:A 15:—  
16:B 17:B 18:— 19:B 20:C  
21:— 22:C 23:C 24:—  
25:B 26:— 27:C 28:C  
29:— 30:C
