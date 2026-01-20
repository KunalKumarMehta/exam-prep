---
title: 'Gram–Schmidt, QR & Least Squares'

---

# PRACTICE SET: Gram–Schmidt, QR & Least Squares

--------------------------------------------------
SECTION A: CONCEPTUAL QUESTIONS (10 MCQs)
--------------------------------------------------

Q1 (Easy, MCQ)
Why is the Gram–Schmidt process used?
A. To diagonalize a matrix
B. To convert a linearly independent set into an orthonormal set
C. To compute eigenvalues
D. To solve nonlinear systems

Q2 (Easy, MCQ)
Which of the following conditions is required for Gram–Schmidt to work?
A. Vectors must be orthogonal
B. Vectors must be orthonormal
C. Vectors must be linearly independent
D. Vectors must be eigenvectors

Q3 (Medium, MCQ)
In QR factorization A = QR, which statement is always true?
A. Q is upper triangular
B. R has orthonormal columns
C. Q has orthonormal columns
D. R is symmetric

Q4 (Medium, MCQ)
What does the R matrix represent in QR factorization?
A. Eigenvalues of A
B. Coefficients from Gram–Schmidt projections
C. Singular values of A
D. Basis vectors of column space

Q5 (Medium, MCQ)
Which problem does QR factorization help solve efficiently?
A. Matrix inversion
B. Least squares problems
C. Determinant computation
D. Eigenvalue problems

Q6 (Medium, MCQ)
Why is solving least squares using QR preferred over normal equations?
A. QR is faster for small matrices
B. QR avoids squaring the condition number
C. QR gives exact solutions always
D. QR avoids matrix multiplication

Q7 (Hard, MCQ)
Which matrix property improves numerical stability in QR-based least squares?
A. Orthogonality of Q
B. Diagonal dominance of R
C. Symmetry of A
D. Sparsity of A

Q8 (Hard, MCQ)
If A has nearly linearly dependent columns, Gram–Schmidt may fail mainly due to:
A. Rank deficiency
B. Floating-point roundoff errors
C. Incorrect normalization
D. Large eigenvalues

Q9 (Hard, MCQ)
Modified Gram–Schmidt is preferred over classical Gram–Schmidt because it:
A. Uses fewer operations
B. Is conceptually simpler
C. Is numerically more stable
D. Produces diagonal R

Q10 (Medium, MCQ)
In least squares via QR, the solution x minimizes:
A. ‖Ax‖
B. ‖x‖
C. ‖Ax − b‖
D. ‖Qx − b‖

--------------------------------------------------
SECTION B: NUMERICAL / PROBLEM SOLVING (20 QUESTIONS)
--------------------------------------------------

Q11 (Easy, MCQ)
Apply one step of Gram–Schmidt to vectors
v₁ = (1, 0), v₂ = (1, 1).
What is the normalized first basis vector q₁?
A. (1, 0)
B. (0, 1)
C. (1/√2, 1/√2)
D. (1, 1)

Q12 (Easy, Manual Input)
Normalize the vector v = (3, 4).  
Write the normalized vector.

Q13 (Easy, MCQ)
If Q has orthonormal columns, then QᵀQ equals:
A. 0
B. Q
C. I
D. R

Q14 (Medium, MCQ)
Given orthonormal vectors q₁, q₂, what is proj_{q₁}(v)?
A. (vᵀq₁) q₂
B. (vᵀq₁) q₁
C. (q₁ᵀq₁) v
D. v − q₁

Q15 (Medium, Manual Input)
Apply Gram–Schmidt to the vectors
v₁ = (1, 1), v₂ = (1, −1)
and write the resulting orthonormal basis.

Q16 (Medium, MCQ)
For A = QR, where A is m×n with m > n, what is the size of R?
A. m×m
B. n×n
C. m×n
D. n×m

Q17 (Medium, Manual Input)
Given
A = [[1, 1],
     [0, 1],
     [0, 0]]
and its QR factorization A = QR,
solve the least squares problem Ax ≈ b for b = (1, 1, 0).

Q18 (Medium, MCQ)
Which equation is solved after QR factorization in least squares?
A. Ax = b
B. Rx = Qᵀb
C. Qx = b
D. RQx = b

Q19 (Hard, Manual Input)
Compute the QR factorization of
A = [[1, 1],
     [1, 0],
     [1, −1]]
using Gram–Schmidt.

Q20 (Medium, MCQ)
Which norm is minimized in least squares problems?
A. ℓ₁ norm
B. ℓ₂ norm
C. ℓ∞ norm
D. Frobenius norm

Q21 (Hard, Manual Input)
Using QR factorization, solve the least squares problem
Ax ≈ b where
A = [[1, 1],
     [1, 2],
     [1, 3]],
b = (1, 2, 2).

Q22 (Medium, MCQ)
Why does orthogonality help numerical stability?
A. Reduces rounding errors
B. Eliminates subtraction
C. Avoids division
D. Ensures sparsity

Q23 (Hard, MCQ)
Which step of Gram–Schmidt is most sensitive to numerical errors?
A. Normalization
B. Vector subtraction
C. Projection computation
D. Matrix multiplication

Q24 (Medium, Manual Input)
Find Qᵀb given
Q = [ [1/√2, 1/√2],
      [1/√2, −1/√2] ],
b = (2, 0).

Q25 (Hard, Manual Input)
Explain (mathematically) why solving least squares via normal equations
(AᵀA)x = Aᵀb
is less numerically stable than QR-based methods.

Q26 (Medium, MCQ)
If columns of A are orthonormal, then the least squares solution is:
A. x = Aᵀb
B. x = (AᵀA)⁻¹b
C. x = Ab
D. x = 0

Q27 (Hard, Manual Input)
Construct a matrix A with nearly linearly dependent columns and explain
how this affects Gram–Schmidt numerically.

Q28 (Medium, MCQ)
Which decomposition avoids forming AᵀA explicitly?
A. LU
B. Cholesky
C. QR
D. Eigen decomposition

Q29 (Medium, Manual Input)
Given R from QR factorization as
R = [[2, 1],
     [0, 1]],
solve Rx = (3, 1).

Q30 (Hard, MCQ)
Which statement best summarizes numerical stability in QR?
A. QR reduces computational cost
B. QR avoids floating point arithmetic
C. QR preserves orthogonality under rounding
D. QR guarantees exact solutions

--------------------------------------------------
END OF PRACTICE SET
--------------------------------------------------


SOLUTIONS: Gram–Schmidt, QR & Least Squares
==========================================

--------------------------------------------------
SECTION A: CONCEPTUAL QUESTIONS (Q1–Q10)
--------------------------------------------------

Q1 Solution
Correct Answer: B

Explanation:
Gram–Schmidt takes a linearly independent set and converts it into an
orthonormal set spanning the same subspace.
It does NOT diagonalize matrices or compute eigenvalues.

----------------------------------------

Q2 Solution
Correct Answer: C

Explanation:
If vectors are linearly dependent, some vector becomes zero after projection
subtraction, making normalization impossible.

----------------------------------------

Q3 Solution
Correct Answer: C

Explanation:
In A = QR:
• Q has orthonormal columns (QᵀQ = I)
• R is upper triangular

----------------------------------------

Q4 Solution
Correct Answer: B

Explanation:
Entries of R are inner products produced during Gram–Schmidt:
rᵢⱼ = qᵢᵀ vⱼ

----------------------------------------

Q5 Solution
Correct Answer: B

Explanation:
QR is primarily used to solve least squares problems efficiently and stably.

----------------------------------------

Q6 Solution
Correct Answer: B

Explanation:
Normal equations square the condition number:
cond(AᵀA) = cond(A)²
QR avoids this amplification.

----------------------------------------

Q7 Solution
Correct Answer: A

Explanation:
Orthogonality preserves vector lengths and angles under floating-point arithmetic,
improving numerical stability.

----------------------------------------

Q8 Solution
Correct Answer: B

Explanation:
Nearly dependent vectors cause catastrophic cancellation due to floating-point
roundoff in classical Gram–Schmidt.

----------------------------------------

Q9 Solution
Correct Answer: C

Explanation:
Modified Gram–Schmidt reduces accumulation of roundoff errors by orthogonalizing
one vector at a time.

----------------------------------------

Q10 Solution
Correct Answer: C

Explanation:
Least squares finds x minimizing the residual:
‖Ax − b‖₂

--------------------------------------------------
SECTION B: NUMERICAL / PROBLEM SOLVING (Q11–Q30)
--------------------------------------------------

Q11 Solution
v₁ = (1,0)

‖v₁‖ = 1

q₁ = v₁ / ‖v₁‖ = (1,0)

Correct Answer: A

----------------------------------------

Q12 Solution
v = (3,4)

‖v‖ = √(3² + 4²) = √25 = 5

Normalized vector:
(3/5, 4/5)

----------------------------------------

Q13 Solution
If Q has orthonormal columns:
QᵀQ = I

Correct Answer: C

----------------------------------------

Q14 Solution
Projection formula:
proj_q(v) = (vᵀq) q

Correct Answer: B

----------------------------------------

Q15 Solution
v₁ = (1,1)
‖v₁‖ = √2
q₁ = (1/√2, 1/√2)

v₂ = (1,−1)

Projection:
proj_q₁(v₂) = ((1,−1)·q₁) q₁ = 0

So u₂ = v₂

‖u₂‖ = √2
q₂ = (1/√2, −1/√2)

Final orthonormal basis:
{ (1/√2, 1/√2), (1/√2, −1/√2) }

----------------------------------------

Q16 Solution
If A is m×n with m > n:
R is n×n

Correct Answer: B

----------------------------------------

Q17 Solution
A = [[1,1],
     [0,1],
     [0,0]]

b = (1,1,0)

From QR least squares:
Solve Rx = Qᵀb

Result:
x = (0,1)

----------------------------------------

Q18 Solution
After QR:
Ax ≈ b → QRx ≈ b
Multiply by Qᵀ:

Rx = Qᵀb

Correct Answer: B

----------------------------------------

Q19 Solution
A columns:
a₁ = (1,1,1)
a₂ = (1,0,−1)

q₁ = a₁ / ‖a₁‖ = (1/√3)(1,1,1)

Projection:
proj_q₁(a₂) = (a₂·q₁) q₁ = 0

Thus q₂ = a₂ / ‖a₂‖ = (1/√2)(1,0,−1)

Q = [q₁ q₂]
R =
[ √3    0
  0   √2 ]

----------------------------------------

Q20 Solution
Least squares minimizes ℓ₂ norm:
‖Ax − b‖₂

Correct Answer: B

----------------------------------------

Q21 Solution
A = [[1,1],
     [1,2],
     [1,3]]

b = (1,2,2)

QR → solve Rx = Qᵀb

Final solution:
x = (0.67, 0.5) approximately

----------------------------------------

Q22 Solution
Correct Answer: A

Explanation:
Orthogonality prevents error magnification and preserves numerical accuracy.

----------------------------------------

Q23 Solution
Correct Answer: B

Explanation:
Subtraction of nearly equal vectors causes loss of significant digits.

----------------------------------------

Q24 Solution
Qᵀ =
[ 1/√2  1/√2
  1/√2 −1/√2 ]

Qᵀb =
( (2/√2), (2/√2) ) = (√2, √2)

----------------------------------------

Q25 Solution
Normal equations square condition number:
cond(AᵀA) = cond(A)²

QR avoids forming AᵀA, preserving numerical accuracy.

----------------------------------------

Q26 Solution
If A has orthonormal columns:
AᵀA = I

Least squares solution:
x = Aᵀb

Correct Answer: A

----------------------------------------

Q27 Solution
Example:
A = [ [1, 1.000001],
      [1, 1],
      [1, 0.999999] ]

Columns are nearly dependent → subtraction in Gram–Schmidt causes severe
roundoff error, degrading orthogonality.

----------------------------------------

Q28 Solution
QR avoids forming AᵀA

Correct Answer: C

----------------------------------------

Q29 Solution
R =
[2 1
 0 1]

Solve:
x₂ = 1
x₁ = (3 − 1)/2 = 1

Solution:
x = (1,1)

----------------------------------------

Q30 Solution
Correct Answer: C

Explanation:
QR preserves orthogonality even with rounding errors, ensuring stability.

--------------------------------------------------
FINAL ANSWER KEY
--------------------------------------------------

Q1 B   Q2 C   Q3 C   Q4 B   Q5 B
Q6 B   Q7 A   Q8 B   Q9 C   Q10 C
Q11 A  Q12 (3/5,4/5)  Q13 C  Q14 B  Q15 ✓
Q16 B  Q17 x=(0,1)   Q18 B  Q19 ✓  Q20 B
Q21 ✓  Q22 A  Q23 B  Q24 (√2,√2)
Q25 ✓  Q26 A  Q27 ✓  Q28 C  Q29 (1,1)
Q30 C
