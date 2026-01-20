---
title: 'Eigenvalues, Eigenvectors & Applications'

---

=====================================================
# PRACTICE SHEET
# Lecture: Eigenvalues, Eigenvectors & Applications

=====================================================
SECTION A: CONCEPTUAL QUESTIONS (MCQ ONLY)
=====================================================

Q1 (Easy, MCQ)
Which of the following best defines an eigenvector of a matrix A?
A) Any vector whose magnitude changes under A  
B) A vector whose direction remains unchanged under A  
C) A vector orthogonal to all columns of A  
D) A vector whose dot product with A is zero  

-----------------------------------------------------

Q2 (Easy, MCQ)
If Av = λv, the scalar λ is called:
A) Invariant direction  
B) Stretch factor  
C) Eigenvector  
D) Basis coefficient  

-----------------------------------------------------

Q3 (Medium, MCQ)
Which of the following geometric interpretations is correct?
A) Eigenvectors represent directions that rotate under A  
B) Eigenvectors represent invariant directions under A  
C) Eigenvectors always lie on coordinate axes  
D) Eigenvectors only exist for symmetric matrices  

-----------------------------------------------------

Q4 (Medium, MCQ)
If λ = 1 is an eigenvalue of A, then the corresponding eigenvectors:
A) Reverse direction  
B) Collapse to zero  
C) Remain unchanged after transformation  
D) Become orthogonal  

-----------------------------------------------------

Q5 (Medium, MCQ)
Which statement about stretch factors is TRUE?
A) Stretch factors are always positive  
B) Stretch factors indicate scaling along eigenvectors  
C) Stretch factors determine the determinant directly  
D) Stretch factors depend on the choice of basis  

-----------------------------------------------------

Q6 (Medium, MCQ)
The characteristic equation of a matrix A is obtained from:
A) det(A) = 0  
B) det(A − λI) = 0  
C) A − λ = 0  
D) A² − λI = 0  

-----------------------------------------------------

Q7 (Hard, MCQ)
If a vector changes direction but not magnitude after transformation, then:
A) λ = −1  
B) λ = 1  
C) λ = 0  
D) λ > 1  

-----------------------------------------------------

Q8 (Hard, MCQ)
Which of the following matrices must have at least one real eigenvalue?
A) Any 2×2 real matrix  
B) Any diagonal matrix  
C) Any orthogonal matrix  
D) Any real matrix with odd dimension  

-----------------------------------------------------

Q9 (Hard, MCQ)
If v is an eigenvector of A with eigenvalue λ, then v represents:
A) A direction invariant up to scaling  
B) A direction invariant up to rotation  
C) A zero-energy direction  
D) A null-space vector  

-----------------------------------------------------

Q10 (Medium, MCQ)
Why is det(A − λI) used instead of det(A)?
A) To remove eigenvectors  
B) To isolate invariant directions  
C) To find non-trivial solutions of (A − λI)v = 0  
D) To diagonalize A  

=====================================================
SECTION B: NUMERICAL / PROBLEM SOLVING
=====================================================

Q11 (Easy, MCQ)
Find the eigenvalues of:
A = [ 3  0
      0  2 ]

A) {1, 6}  
B) {3, 2}  
C) {0, 5}  
D) {−3, −2}  

-----------------------------------------------------

Q12 (Easy, Manual Input)
For the matrix:
A = [ 4  0
      0  1 ]
State the eigenvalues.

Answer: __________

-----------------------------------------------------

Q13 (Easy, MCQ)
For A = [ 2  0
          0  2 ],
the stretch factor along any eigenvector is:
A) 0  
B) 1  
C) 2  
D) −2  

-----------------------------------------------------

Q14 (Medium, MCQ)
Find the eigenvalues of:
A = [ 1  2
      0  3 ]

A) {1, 3}  
B) {2, 3}  
C) {−1, −3}  
D) {0, 4}  

-----------------------------------------------------

Q15 (Medium, Manual Input)
For the matrix:
A = [ 5  0
      0 −1 ]
Identify the invariant directions.

Answer: __________

-----------------------------------------------------

Q16 (Medium, MCQ)
If λ = −2 is an eigenvalue, the geometric effect along its eigenvector is:
A) Stretch by 2, same direction  
B) Shrink and rotate  
C) Stretch by 2, reverse direction  
D) Collapse to zero  

-----------------------------------------------------

Q17 (Medium, Manual Input)
Compute the characteristic equation of:
A = [ 2  1
      1  2 ]

Answer: __________

-----------------------------------------------------

Q18 (Medium, MCQ)
Which vector is an eigenvector of:
A = [ 3  0
      0  1 ] ?

A) (1, 0)  
B) (0, 1)  
C) (1, 1)  
D) Both A and B  

-----------------------------------------------------

Q19 (Medium, Manual Input)
For the matrix:
A = [ 0  1
      1  0 ]
Find the eigenvalues.

Answer: __________

-----------------------------------------------------

Q20 (Hard, MCQ)
The matrix:
A = [ 1  1
      1  1 ]
has eigenvalues:
A) {0, 1}  
B) {1, 2}  
C) {0, 2}  
D) {−1, 2}  

-----------------------------------------------------

Q21 (Hard, Manual Input)
Find the eigenvalues of:
A = [ 2  1
      1  2 ]

Answer: __________

-----------------------------------------------------

Q22 (Medium, MCQ)
If an eigenvalue is zero, the transformation:
A) Preserves direction  
B) Collapses vectors onto a lower dimension  
C) Rotates vectors  
D) Is invertible  

-----------------------------------------------------

Q23 (Hard, Manual Input)
Find the characteristic equation of:
A = [ 4  1
      2  3 ]

Answer: __________

-----------------------------------------------------

Q24 (Medium, MCQ)
Eigenvectors corresponding to different eigenvalues are:
A) Always orthogonal  
B) Always linearly independent  
C) Always parallel  
D) Always unit vectors  

-----------------------------------------------------

Q25 (Medium, Manual Input)
For A = [ −1  0
          0  2 ],
state the stretch factors and their geometric effect.

Answer: __________

-----------------------------------------------------

Q26 (Hard, MCQ)
If λ > 1, the transformation along its eigenvector:
A) Shrinks  
B) Preserves length  
C) Stretches  
D) Reverses direction  

-----------------------------------------------------

Q27 (Hard, Manual Input)
For the matrix:
A = [ 1  0
      0 −1 ],
describe the invariant directions.

Answer: __________

-----------------------------------------------------

Q28 (Medium, MCQ)
The number of eigenvalues of an n×n matrix (counting multiplicity) is:
A) n  
B) n²  
C) ≤ n  
D) ≥ n  

-----------------------------------------------------

Q29 (Hard, MCQ)
If λ = −1 is an eigenvalue, the transformation:
A) Rotates by 90°  
B) Reflects through origin  
C) Collapses to zero  
D) Preserves direction  

-----------------------------------------------------

Q30 (Medium, Manual Input)
Explain why eigenvectors represent invariant directions geometrically.

Answer: __________

=====================================================
END OF PRACTICE SHEET
=====================================================

=====================================================
DETAILED SOLUTIONS & ANSWER KEY
Lecture: Eigenvalues, Eigenvectors & Applications
=====================================================

-----------------------------------------------------
SECTION A: CONCEPTUAL QUESTIONS
-----------------------------------------------------

Q1.
Correct Answer: B

Explanation:
An eigenvector v satisfies Av = λv.
This means the direction of v does NOT change, only its length (scaling).
Hence, it represents an invariant direction.

-----------------------------------------------------

Q2.
Correct Answer: B

Explanation:
In Av = λv, λ tells how much v is scaled.
Geometrically, λ is the stretch (or shrink) factor.

-----------------------------------------------------

Q3.
Correct Answer: B

Explanation:
Eigenvectors point along directions that remain invariant under the transformation A.
They may stretch, shrink, or flip, but do not rotate.

-----------------------------------------------------

Q4.
Correct Answer: C

Explanation:
If λ = 1, then Av = v.
So vectors remain unchanged after transformation.

-----------------------------------------------------

Q5.
Correct Answer: B

Explanation:
Stretch factors indicate how much eigenvectors are scaled.
They can be positive, negative, or zero.

-----------------------------------------------------

Q6.
Correct Answer: B

Explanation:
Eigenvalues come from non-trivial solutions of:
(A − λI)v = 0
This happens when det(A − λI) = 0.

-----------------------------------------------------

Q7.
Correct Answer: A

Explanation:
If direction reverses but magnitude stays same:
Av = −v ⇒ λ = −1.

-----------------------------------------------------

Q8.
Correct Answer: D

Explanation:
Any real matrix of odd dimension must have at least one real eigenvalue
(odd-degree characteristic polynomial).

-----------------------------------------------------

Q9.
Correct Answer: A

Explanation:
Eigenvectors are directions invariant up to scaling.
Scaling may include sign reversal.

-----------------------------------------------------

Q10.
Correct Answer: C

Explanation:
det(A − λI) = 0 ensures non-zero solutions to (A − λI)v = 0,
which defines eigenvectors.

-----------------------------------------------------
SECTION B: NUMERICAL / PROBLEM SOLVING
-----------------------------------------------------

Q11.
Matrix:
[ 3  0
  0  2 ]

Eigenvalues are diagonal entries.

Answer: B ({3, 2})

-----------------------------------------------------

Q12.
Matrix:
[ 4  0
  0  1 ]

Eigenvalues = diagonal entries.

Answer: 4, 1

-----------------------------------------------------

Q13.
Matrix:
[ 2  0
  0  2 ]

Av = 2v for any non-zero v.

Answer: C (2)

-----------------------------------------------------

Q14.
Matrix:
[ 1  2
  0  3 ]

Characteristic equation:
|1−λ  2 |
| 0  3−λ| = (1−λ)(3−λ)

Eigenvalues: 1, 3

Answer: A

-----------------------------------------------------

Q15.
Matrix:
[ 5  0
  0 −1 ]

Invariant directions:
x-axis (eigenvalue 5)
y-axis (eigenvalue −1)

Answer:
Along (1,0) and (0,1)

-----------------------------------------------------

Q16.
Correct Answer: C

Explanation:
λ = −2 means magnitude doubles and direction reverses.

-----------------------------------------------------

Q17.
Matrix:
[ 2  1
  1  2 ]

A − λI =
[2−λ  1
 1   2−λ]

det = (2−λ)² − 1
= λ² − 4λ + 3

Answer:
λ² − 4λ + 3 = 0

-----------------------------------------------------

Q18.
Matrix:
[ 3  0
  0  1 ]

Eigenvectors align with axes.

Answer: D (Both A and B)

-----------------------------------------------------

Q19.
Matrix:
[ 0  1
  1  0 ]

Characteristic equation:
|−λ  1 |
| 1  −λ| = λ² − 1

Eigenvalues:
λ = ±1

Answer: 1, −1

-----------------------------------------------------

Q20.
Matrix:
[ 1  1
  1  1 ]

Characteristic equation:
|1−λ  1 |
| 1  1−λ| = (1−λ)² − 1
= λ² − 2λ

Eigenvalues:
0, 2

Answer: C

-----------------------------------------------------

Q21.
Same matrix as Q17.

Eigenvalues:
λ² − 4λ + 3 = 0
⇒ λ = 1, 3

Answer: 1, 3

-----------------------------------------------------

Q22.
Correct Answer: B

Explanation:
λ = 0 collapses vectors onto a lower-dimensional subspace.

-----------------------------------------------------

Q23.
Matrix:
[ 4  1
  2  3 ]

A − λI =
[4−λ  1
 2   3−λ]

det = (4−λ)(3−λ) − 2
= λ² − 7λ + 10

Answer:
λ² − 7λ + 10 = 0

-----------------------------------------------------

Q24.
Correct Answer: B

Explanation:
Eigenvectors corresponding to distinct eigenvalues are always linearly independent.

-----------------------------------------------------

Q25.
Matrix:
[ −1  0
   0  2 ]

Stretch factors:
−1 → flip direction
2 → stretch by factor 2

Answer:
Flip along x-axis, stretch along y-axis

-----------------------------------------------------

Q26.
Correct Answer: C

Explanation:
λ > 1 stretches vectors along eigenvector direction.

-----------------------------------------------------

Q27.
Matrix:
[ 1  0
  0 −1 ]

Invariant directions:
x-axis (unchanged)
y-axis (flipped)

Answer:
Along coordinate axes

-----------------------------------------------------

Q28.
Correct Answer: A

Explanation:
An n×n matrix has exactly n eigenvalues (counting multiplicity).

-----------------------------------------------------

Q29.
Correct Answer: B

Explanation:
λ = −1 flips vector through origin.

-----------------------------------------------------

Q30.
Answer:
Eigenvectors represent invariant directions because applying A only scales them:
Av = λv.
The direction remains unchanged (up to sign), making them geometrically invariant.

=====================================================
FINAL ANSWER KEY (Quick Scan)
=====================================================

1.B  2.B  3.B  4.C  5.B  
6.B  7.A  8.D  9.A  10.C  
11.B 12.{4,1} 13.C 14.A 15.Axes  
16.C 17.λ²−4λ+3 18.D 19.±1 20.C  
21.{1,3} 22.B 23.λ²−7λ+10 24.B 25.Flip/Stretch  
26.C 27.Axes 28.A 29.B 30.Invariant scaling

=====================================================
