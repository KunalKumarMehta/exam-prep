---
title: 'Determinants, Cofactors & Inverse'

---

PRACTICE SHEET – LECTURE 4
Determinants, Cofactors & Inverse
(SECTION: EASY QUESTIONS ONLY – Q1 to Q8)

Topics: Determinants formally • Cofactor expansion • Adjoint matrix • Inverse using adjoint/determinant • det(AB) = det(A)\,det(B) • When inverse exists


------------------------------------------------------------
EASY (8 QUESTIONS)
------------------------------------------------------------

Q1. (Conceptual, Single-correct)  
For a $2 \times 2$ matrix
$$
A = \begin{bmatrix}
a & b \\
c & d
\end{bmatrix},
$$
the determinant $\det(A)$ is:
a) $a + d$  
b) $ad - bc$  
c) $ab - cd$  
d) $ac - bd$  


Q2. (Conceptual, Single-correct)  
For a $2 \times 2$ matrix $A$ representing a linear transformation on $\mathbb{R}^2$, the determinant $\det(A)$ represents:  
a) The change in length of every vector  
b) The number of solutions of $Ax = b$  
c) The area-scaling factor (with sign indicating orientation)  
d) Only the rotation angle  


Q3. (Problem-solving, Single-correct)  
Compute the determinant of
$$
A = \begin{bmatrix}
2 & 3 \\
1 & 4
\end{bmatrix}.
$$
a) $5$  
b) $8$  
c) $-5$  
d) $-2$  


Q4. (Problem-solving, Single-correct)  
Which of the following $2 \times 2$ matrices has determinant $0$?  
a)
$$
\begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
2 & 4 \\
1 & 2
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
0 & 1 \\
1 & 0
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
$$


Q5. (Conceptual, Single-correct)  
A square matrix $A$ is invertible if and only if:  
a) $A$ has at least one zero entry  
b) $\det(A) \neq 0$  
c) $\det(A) = 0$  
d) All diagonal entries of $A$ are positive  


Q6. (Problem-solving, Single-correct)  
Let
$$
A = \begin{bmatrix}
1 & 2 \\
0 & 1
\end{bmatrix}.
$$
Which of the following is $A^{-1}$?  
a)
$$
\begin{bmatrix}
1 & -2 \\
0 & 1
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1 & 2 \\
0 & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
1 & 0 \\
-2 & 1
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
-1 & 2 \\
0 & 1
\end{bmatrix}
$$


Q7. (Conceptual, Single-correct)  
If a square matrix $A$ has a row of all zeros, then:  
a) $\det(A)$ is always $1$  
b) $\det(A)$ is always $0$  
c) $\det(A)$ depends only on the other rows  
d) $\det(A)$ is always $-1$  


Q8. (Conceptual, Single-correct)  
Which statement is TRUE about determinants?  
a) $\det(A + B) = \det(A) + \det(B)$ for all square $A, B$  
b) $\det(AB) = \det(A)\,\det(B)$ for all square $A, B$ of same size  
c) $\det(kA) = k\,\det(A)$ for all scalars $k$ and square $A$ (any size)  
d) $\det(A)$ is always non-negative for real matrices  

------------------------------------------------------------
MEDIUM (15 QUESTIONS)
------------------------------------------------------------

Q9. (Problem-solving, Single-correct)
Compute the determinant of
$$
A = \begin{bmatrix}
3 & 1 \\
5 & -2
\end{bmatrix}.
$$
a) −11  
b) 11  
c) −13  
d) 13  


Q10. (Problem-solving, Single-correct)
Compute $\det(A)$ for
$$
A = \begin{bmatrix}
4 & 2 & 1 \\
0 & 3 & -1 \\
0 & 0 & 2
\end{bmatrix}.
$$
a) 24  
b) −24  
c) 36  
d) 12  


Q11. (Conceptual, Single-correct)
Expanding across the first row of a $3 \times 3$ matrix requires:
a) Multiplying entries by corresponding cofactors  
b) Multiplying entries by corresponding minors only  
c) Expanding using only diagonal entries  
d) Expanding using only last column entries  


Q12. (Problem-solving, Single-correct)  
Let
$$
A = \begin{bmatrix}
2 & 1 & 0 \\
4 & 3 & 1 \\
0 & 2 & 1
\end{bmatrix}.
$$
Compute the minor $M_{23}$ (delete row 2 and column 3).
a) $6$  
b) $-6$  
c) $2$  
d) $4$  


Q13. (Problem-solving, Single-correct)  
For the same matrix $A$ in Q12, compute the **cofactor $C_{22}$**.  
a) $6$  
b) $-6$  
c) $2$  
d) $-2$  


Q14. (Problem-solving, Single-correct)  
Compute $\det(A)$ (e.g. via cofactor expansion across the second row) for
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
0 & 0 & 6
\end{bmatrix}.
$$
a) $0$  
b) $3$  
c) $-12$  
d) $6$  


Q15. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & 2 \\
3 & 4
\end{bmatrix}.
$$
Compute the adjoint $\text{adj}(A)$.
a)
$$
\begin{bmatrix}
4 & -2 \\
-3 & 1
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
4 & 3 \\
2 & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
4 & 3 \\
2 & 1
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
4 & -3 \\
-2 & 1
\end{bmatrix}
$$


Q16. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & 0 \\
-2 & 3
\end{bmatrix}.
$$
Compute $A^{-1}$ using adjoint/determinant.
a)
$$
\begin{bmatrix}
3 & 0 \\
2 & 1
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
3 & 0 \\
2 & 1
\end{bmatrix}
$$
c)
$$
\frac{1}{3}
\begin{bmatrix}
3 & 0 \\
2 & 1
\end{bmatrix}
$$
d)
$$
\frac{1}{3}
\begin{bmatrix}
3 & 0 \\
-2 & 1
\end{bmatrix}
$$


Q17. (Conceptual, Single-correct)
If $\det(A) = 5$ and $\det(B) = -2$, then $\det(AB)$ equals:
a) 10  
b) −10  
c) −5  
d) 7  


Q18. (Problem-solving, Single-correct)  
Compute the determinant of
$$
A = \begin{bmatrix}
1 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 4
\end{bmatrix}.
$$
a) $-4$  
b) $-8$  
c) $4$  
d) $8$  


Q19. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
0 & 0 & k
\end{bmatrix}.
$$
For which value of $k$ is $A$ **non-invertible**?
a) $k = 1$  
b) $k = 0$  
c) $k = 2$  
d) $k = -3$  


Q20. (Conceptual, Single-correct)
If matrix $A$ is invertible, then:
a) $\det(A) = 0$  
b) $\det(A) \neq 0$  
c) $A$ has at least one zero entry  
d) $A$ has only positive entries  


Q21. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
a & 0 \\
0 & b
\end{bmatrix},
$$
with $ab \neq 0$. Then $A^{-1}$ equals:
a)
$$
\begin{bmatrix}
a & 0 \\
0 & b
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1/a & 0 \\
0 & 1/b
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
b & 0 \\
0 & a
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
0 & 1/a \\
1/b & 0
\end{bmatrix}
$$


Q22. (Conceptual, Multi-correct)
Which conditions guarantee $A$ is **not invertible**?
a) $\det(A) = 0$  
b) Two rows of $A$ are proportional  
c) $A$ has at least two negative diagonal entries  
d) A full row of zeros exists  


Q23. (Problem-solving, Single-correct)  
Compute $\det(A)$ for
$$
A = \begin{bmatrix}
1 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 17
\end{bmatrix}.
$$
a) $34$  
b) $-34$  
c) $28$  
d) $-28$  


------------------------------------------------------------
HARD (7 QUESTIONS) – Q24 TO Q30
------------------------------------------------------------

Q24. (Problem-solving, Single-correct)
Compute the determinant of the $4 \times 4$ matrix
$$
A = \begin{bmatrix}
1 & 2 & 0 & 0 \\
0 & 3 & 4 & 0 \\
0 & 0 & 0 & 5 \\
2 & 0 & 0 & 0
\end{bmatrix}.
$$
a) $80$  
b) $-80$  
c) $40$  
d) $-40$  


Q25. (Problem-solving, Single-correct)
For which value of $k$ is the following $4 \times 4$ matrix **not invertible**?
$$
B = \begin{bmatrix}
1 & 0 & 0 & 0 \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
1 & 1 & 1 & k
\end{bmatrix}.
$$
a) $k = -1$  
b) $k = 0$  
c) $k = 1$  
d) $k = 2$  


Q26. (Problem-solving, Single-correct)
Let
$$
C = \begin{bmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1
\end{bmatrix}.
$$
Using adjoint/determinant idea (conceptually), the inverse $C^{-1}$ is:
a)
$$
\frac{1}{2}
\begin{bmatrix}
1 & -1 & 1 \\
1 & 1 & -1 \\
-1 & 1 & 1
\end{bmatrix}
$$
b)
$$
\frac{1}{2}
\begin{bmatrix}
1 & 1 & 1 \\
-1 & 1 & 1 \\
1 & -1 & 1
\end{bmatrix}
$$
c)
$$
\frac{1}{2}
\begin{bmatrix}
1 & -1 & -1 \\
1 & 1 & 1 \\
-1 & 1 & -1
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
1 & -1 & 1 \\
1 & 1 & -1 \\
-1 & 1 & 1
\end{bmatrix}
$$


Q27. (Conceptual, Multi-correct)
Which statements are TRUE for an $n \times n$ matrix $A$ with $\det(A) \neq 0$?
a) $A$ is invertible  
b) The rows of $A$ are linearly independent  
c) $\text{rank}(A) = n$  
d) The homogeneous system $Ax = 0$ has a non-trivial solution  


Q28. (Conceptual, Single-correct)
Let $A$ and $B$ be invertible $n \times n$ matrices. What is $\det(AB^{-1})$?
a) $\dfrac{\det(A)}{\det(B)}$  
b) $\det(A)\det(B)$  
c) $\dfrac{\det(B)}{\det(A)}$  
d) $\dfrac{1}{\det(A)\det(B)}$  


Q29. (Conceptual, Multi-correct)
Which identities are TRUE for any square matrix $A$ of size $n \times n$?
a) $A \, \text{adj}(A) = \det(A)\,I_n$  
b) $\text{adj}(A)\,A = \det(A)\,I_n$  
c) If $\det(A) \neq 0$ then $A^{-1} = \dfrac{1}{\det(A)} \,\text{adj}(A)$  
d) If $\det(A) = 0$ then $\text{adj}(A) = 0$ (the zero matrix)  


Q30. (Problem-solving, Single-correct)
Let $A$ be a $3 \times 3$ matrix with $\det(A) = 5$. Consider the matrix
$$
B = 2A.
$$
What is $\det(B)$?
a) $10$  
b) $20$  
c) $40$  
d) $-10$  



============================================================
FULL ANSWER KEY
============================================================

Q1  b  
Q2  c  
Q3  a  
Q4  b  
Q5  b  
Q6  a  
Q7  b  
Q8  b  

Q9  a  
Q10 a  
Q11 a  
Q12 d  
Q13 c  
Q14 d  
Q15 a  
Q16 c  
Q17 b  
Q18 d  
Q19 b  
Q20 b  
Q21 b  
Q22 a, b, d  
Q23 a  

Q24 b  
Q25 b  
Q26 a  
Q27 a, b, c  
Q28 a  
Q29 a, b, c  
Q30 c  



============================================================
STEP-BY-STEP SOLUTIONS (ALL 30)
============================================================

--------------------
EASY (Q1–Q8)
--------------------

Q1.  
For $2 \times 2$,
$$
\det\begin{bmatrix} a & b \\ c & d \end{bmatrix} = ad - bc.
$$
Answer: **b**

Q2.  
In $\mathbb{R}^2$, determinant = signed area-scaling factor.  
Answer: **c**

Q3.  
$\det\begin{bmatrix}2 & 3 \\ 1 & 4\end{bmatrix} = 2\cdot4 - 3\cdot1 = 8 - 3 = 5$.  
Answer: **a**

Q4.  
Check each:  
a) $1\cdot4 - 2\cdot3 = 4 - 6 = -2 \neq 0$  
b) $2\cdot2 - 4\cdot1 = 4 - 4 = 0$ ← determinant $0$  
c) $0\cdot0 - 1\cdot1 = -1$  
d) $1\cdot(-1) - 0\cdot0 = -1$  
Answer: **b**

Q5.  
A square matrix is invertible ⇔ $\det(A)\neq 0$.  
Answer: **b**

Q6.  
For $A = \begin{bmatrix}1 & 2\\0 & 1\end{bmatrix}$, known inverse of shear is  
$A^{-1} = \begin{bmatrix}1 & -2\\0 & 1\end{bmatrix}$.  
Check $AA^{-1} = I$.  
Answer: **a**

Q7.  
If any row is all zeros, the determinant is $0$ (volume collapses).  
Answer: **b**

Q8.  
General property: $\det(AB) = \det(A)\det(B)$ (not true for $A+B$).  
Answer: **b**



--------------------
MEDIUM (Q9–Q23, WITH CORRECTED Q12, Q13, Q14, Q18, Q23)
--------------------

Q9.  
$\det\begin{bmatrix}3 & 1 \\ 5 & -2\end{bmatrix} = 3(-2) - 1\cdot5 = -6 - 5 = -11$.  
Answer: **a**

Q10.  
Upper triangular:
$$
A = \begin{bmatrix}
4 & 2 & 1 \\
0 & 3 & -1 \\
0 & 0 & 2
\end{bmatrix}
$$
Determinant = product of diagonal = $4\cdot3\cdot2 = 24$.  
Answer: **a**

Q11.  
Cofactor expansion along the first row:
$$
\det(A) = a_{11}C_{11} + a_{12}C_{12} + a_{13}C_{13},
$$
where $C_{1j}$ are cofactors.  
Answer: **a**

Q12.  
Matrix:
$$
A = \begin{bmatrix}
2 & 1 & 0 \\
4 & 3 & 1 \\
0 & 2 & 1
\end{bmatrix}.
$$
$M_{23}$: delete row 2, column 3 → submatrix
$$
\begin{bmatrix}
2 & 1 \\
0 & 2
\end{bmatrix},
\quad \det = 2\cdot2 - 1\cdot0 = 4.
$$
Answer: **d**

Q13.  
Same $A$. $C_{22} = (-1)^{2+2}M_{22} = (+1)M_{22}$.  
$M_{22}$: delete row 2, col 2 → submatrix
$$
\begin{bmatrix}
2 & 0 \\
0 & 1
\end{bmatrix},\quad \det = 2\cdot1 - 0 = 2.
$$
So $C_{22} = 2$.  
Answer: **c**

Q14.  
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
0 & 0 & 6
\end{bmatrix}
$$
Upper triangular, determinant = $1\cdot1\cdot6 = 6$.  
Answer: **d**

Q15.  
For $2 \times 2$, $\text{adj}(A) = \begin{bmatrix} d & -b \\ -c & a \end{bmatrix}$.  
$A = \begin{bmatrix}1 & 2 \\ 3 & 4\end{bmatrix} \Rightarrow \text{adj}(A)=\begin{bmatrix}4 & -2\\ -3 & 1\end{bmatrix}$.  
Answer: **a**

Q16.  
$A = \begin{bmatrix}1 & 0\\ -2 & 3\end{bmatrix}$.  
$\det(A) = 1\cdot3 - 0 = 3$.  
$\text{adj}(A)=\begin{bmatrix}3 & 0\\ 2 & 1\end{bmatrix}$.  
So $A^{-1} = \dfrac{1}{3}\text{adj}(A) = \dfrac{1}{3}\begin{bmatrix}3 & 0\\ 2 & 1\end{bmatrix}$.  
Answer: **c**

Q17.  
$\det(AB) = \det(A)\det(B) \Rightarrow \det(AB) = 5 \cdot (-2) = -10$.  
Answer: **b**

Q18.  
$$
A = \begin{bmatrix}
1 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 4
\end{bmatrix}
$$
Diagonal ⇒ determinant = product diagonal = $1\cdot2\cdot4 = 8$.  
Answer: **d**

Q19.  
Upper triangular:
$$
\det(A) = 1 \cdot 1 \cdot k = k.
$$
Non-invertible when determinant $=0 \Rightarrow k=0$.  
Answer: **b**

Q20.  
Invertible ⇔ determinant non-zero.  
Answer: **b**

Q21.  
$$
A = \begin{bmatrix}
a & 0 \\
0 & b
\end{bmatrix}, \quad ab \neq 0.
$$
Inverse of diagonal is diagonal of reciprocals:
$$
A^{-1} = \begin{bmatrix} 1/a & 0\\ 0 & 1/b\end{bmatrix}.
$$
Answer: **b**

Q22.  
Non-invertible when any of these holds:
- $\det(A) = 0$  
- two rows proportional ⇒ rows dependent ⇒ det 0  
- full zero row ⇒ det 0  

Having negative diagonal entries (c) doesn’t guarantee non-invertibility.  
Answer: **a, b, d**

Q23.  
$$
A = \begin{bmatrix}
1 & 0 & 0 \\
0 & 2 & 0 \\
0 & 0 & 17
\end{bmatrix},\quad \det(A) = 1\cdot2\cdot17 = 34.
$$
Answer: **a**



--------------------
HARD (Q24–Q30)
--------------------

Q24.  
$$
A = \begin{bmatrix}
1 & 2 & 0 & 0 \\
0 & 3 & 4 & 0 \\
0 & 0 & 0 & 5 \\
2 & 0 & 0 & 0
\end{bmatrix}.
$$
Expand along column 4 (only one non-zero: $a_{34}=5$):
$$
\det(A) = 5 \cdot (-1)^{3+4} \cdot \det(\text{submatrix removing row 3, col 4}).
$$
Factor $(-1)^{7}=-1$. Submatrix is
$$
\begin{bmatrix}
1 & 2 & 0 \\
0 & 3 & 4 \\
2 & 0 & 0
\end{bmatrix}.
$$
Compute this determinant (e.g. expand along column 3: only entry $4$ in row2):
$\det = 4\cdot(-1)^{2+3}\det\begin{bmatrix}1 & 2\\ 2 & 0\end{bmatrix}
= 4(-1)(1\cdot0 -2\cdot2)=4(-1)(-4)=16$.

So $\det(A) = 5\cdot(-1)\cdot16 = -80$.  
Answer: **b**

Q25.  
$$
B = \begin{bmatrix}
1 & 0 & 0 & 0 \\
0 & 1 & 0 & 0 \\
0 & 0 & 1 & 0 \\
1 & 1 & 1 & k
\end{bmatrix}.
$$
This is like identity with last row modified. Determinant is $k$ (you can compute using cofactor expansion along last column).  
Non-invertible ⇔ det = 0 ⇔ $k=0$.  
Answer: **b**

Q26.  
$$
C = \begin{bmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1
\end{bmatrix}.
$$
Compute (by any method) $\det(C)=2$ and the inverse:
$$
C^{-1} =
\frac{1}{2}
\begin{bmatrix}
1 & -1 & 1 \\
1 & 1 & -1 \\
-1 & 1 & 1
\end{bmatrix}.
$$
Matches option (a).  
Answer: **a**

Q27.  
For $\det(A)\neq 0$:
- $A$ invertible ✔  
- Rows linearly independent ✔  
- Rank = $n$ ✔  
- $Ax=0$ has only trivial solution (so statement “has a non-trivial solution” is false)  

Answer: **a, b, c**

Q28.  
$\det(AB^{-1}) = \det(A)\det(B^{-1}) = \det(A)\cdot \dfrac{1}{\det(B)} = \dfrac{\det(A)}{\det(B)}$.  
Answer: **a**

Q29.  
Standard identities:
- $A\text{adj}(A)=\det(A)I_n$ ✔  
- $\text{adj}(A)A=\det(A)I_n$ ✔  
- If $\det(A)\neq 0$, then $A^{-1}=\dfrac{1}{\det(A)}\text{adj}(A)$ ✔  
If $\det(A)=0$, adj$(A)$ is **not** necessarily zero (it can be non-zero for rank-deficient matrices). So (d) is false.  
Answer: **a, b, c**

Q30.  
If $B=2A$ and $A$ is $3\times3$, then
$$
\det(2A) = 2^3 \det(A) = 8 \cdot 5 = 40.
$$
Answer: **c**

============================================================
END OF LECTURE 4 PRACTICE SHEET
============================================================

