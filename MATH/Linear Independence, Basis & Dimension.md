---
title: 'Linear Independence, Basis & Dimension'

---

PRACTICE SHEET – LECTURE 6
Linear Independence, Basis & Dimension
(QUESTIONS ONLY — 30 MCQs)

EASY (Q1–Q8)
------------------------------------------------------------

Q1. (Conceptual)
Which of the following statements defines **linear independence** of vectors $v_1, v_2, \dots, v_k$?
a) They all have different lengths  
b) The only solution to $c_1 v_1 + \dots + c_k v_k = 0$ is $c_1 = \dots = c_k = 0$  
c) They are pairwise orthogonal  
d) They form a basis of $\mathbb{R}^n$  


Q2. (Conceptual)
A set of vectors is linearly **dependent** if:
a) At least one vector is a linear combination of the others  
b) All vectors are orthogonal  
c) Their span is all of $\mathbb{R}^n$  
d) Their determinant is positive  


Q3. (Conceptual)
A **basis** of a vector space is:
a) Any set of vectors with length 1  
b) Any set of independent vectors that spans the space  
c) Any spanning set  
d) Any independent set  


Q4. (Conceptual)
The dimension of a subspace is:
a) The number of rows in any matrix whose columns form that subspace  
b) The maximum number of linearly independent vectors in the subspace  
c) Always equal to the number of variables  
d) Always equal to the number of equations  


Q5. (Conceptual)
If three vectors in $\mathbb{R}^3$ are linearly independent, they:
a) Form a basis of $\mathbb{R}^3$  
b) Must be orthogonal  
c) Must have determinant zero  
d) Must sum to zero  


Q6. (Problem-solving)
Are the vectors
$$
v_1 = \begin{bmatrix}1\\0\\1\end{bmatrix},\quad
v_2 = \begin{bmatrix}2\\1\\3\end{bmatrix}
$$
independent?
a) Yes  
b) No  


Q7. (Problem-solving)
Let
$$
v_1 = \begin{bmatrix}1\\2\\0\end{bmatrix},\;
v_2 = \begin{bmatrix}2\\4\\0\end{bmatrix},\;
v_3 = \begin{bmatrix}3\\6\\0\end{bmatrix}.
$$
The set $\{v_1,v_2,v_3\}$ is:
a) Independent  
b) Dependent  
c) A basis of $\mathbb{R}^3$  
d) Orthogonal  


Q8. (Conceptual)
A set of $k$ linearly independent vectors in an $n$-dimensional space must satisfy:
a) $k > n$  
b) $k = n$  
c) $k \le n$  
d) $k < n$  


MEDIUM (Q9–Q23)
------------------------------------------------------------

Q9. (Problem-solving)
Consider the matrix
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{bmatrix}.
$$
How many pivot columns does $A$ have?
a) 1  
b) 2  
c) 3  
d) 0  


Q10. (Problem-solving)
Using the same matrix $A$ from Q9, the **rank** of $A$ is:
a) 1  
b) 2  
c) 3  
d) 0  


Q11. (Problem-solving)
Let
$$
B = \begin{bmatrix}
1 & 2 & 1 \\
0 & 1 & -1 \\
0 & 0 & 0
\end{bmatrix}.
$$
The rank of $B$ is:
a) 0  
b) 1  
c) 2  
d) 3  


Q12. (Problem-solving)
For the same matrix $B$ in Q11, $\dim(\text{Null}(B))$ equals:
a) 0  
b) 1  
c) 2  
d) 3  


Q13. (Problem-solving)
Find whether the set
$$
\left\{
\begin{bmatrix}1\\1\\0\end{bmatrix},
\begin{bmatrix}2\\0\\1\end{bmatrix},
\begin{bmatrix}3\\1\\1\end{bmatrix}
\right\}
$$
is linearly independent.
a) Yes  
b) No  


Q14. (Problem-solving)
Consider the matrix
$$
C = \begin{bmatrix}
1 & 2 & 3 \\
1 & 2 & 3 \\
0 & 1 & 1
\end{bmatrix}.
$$
Find $\dim(\text{Col}(C))$.
a) 1  
b) 2  
c) 3  
d) 0  


Q15. (Problem-solving)
For the same matrix $C$, $\dim(\text{Null}(C))$ is:
a) 0  
b) 1  
c) 2  
d) 3  


Q16. (Conceptual)
A basis for the null space of a matrix must:
a) Contain pivot columns  
b) Contain free-variable vectors  
c) Contain the columns of the matrix  
d) Always contain three vectors  


Q17. (Conceptual)
If a set of 3 vectors in $\mathbb{R}^3$ spans $\mathbb{R}^3$, then:
a) They are automatically orthogonal  
b) They are linearly independent  
c) They must contain a zero vector  
d) They must have norm 1  


Q18. (Problem-solving)
Let
$$
D = \begin{bmatrix}
1 & 2 & 1 \\
0 & 1 & 1 \\
0 & 0 & 1
\end{bmatrix}.
$$
Which vector is in $\text{Col}(D)$?
a) $\begin{bmatrix}1\\1\\1\end{bmatrix}$  
b) $\begin{bmatrix}0\\1\\0\end{bmatrix}$  
c) $\begin{bmatrix}3\\2\\1\end{bmatrix}$  
d) $\begin{bmatrix}5\\3\\1\end{bmatrix}$  


Q19. (Problem-solving)
Let basis
$$
B = \left\{
\begin{bmatrix}1\\0\\1\end{bmatrix},
\begin{bmatrix}0\\1\\1\end{bmatrix},
\begin{bmatrix}1\\1\\0\end{bmatrix}
\right\}.
$$
Find the coordinates of
$v = \begin{bmatrix}3\\2\\1\end{bmatrix}$ relative to $B$, written as a column vector.
a)
$\begin{bmatrix}1\\1\\1\end{bmatrix}$  
b)
$\begin{bmatrix}2\\0\\1\end{bmatrix}$  
c)
$\begin{bmatrix}1\\0\\2\end{bmatrix}$  
d)
$\begin{bmatrix}0\\1\\2\end{bmatrix}$  


Q20. (Problem-solving)
Let
$$
E = \begin{bmatrix}
1 & 0 & 2 \\
0 & 1 & -1 \\
0 & 0 & 0
\end{bmatrix}.
$$
Rank$(E)$ equals:
a) 0  
b) 1  
c) 2  
d) 3  


Q21. (Problem-solving)
For the same matrix $E$, $\dim(\text{Null}(E))$ equals:
a) 0  
b) 1  
c) 2  
d) 3  


Q22. (Conceptual)
The **dimension theorem** states:
a) $\dim(\text{Col}(A)) + \dim(\text{Null}(A)) = m$  
b) $\dim(\text{Col}(A)) + \dim(\text{Null}(A)) = n$  
c) $\dim(\text{Col}(A)) = \dim(\text{Null}(A))$  
d) $\dim(\text{Null}(A)) = \text{rank}(A)$  


Q23. (Problem-solving)
Which set is a basis for $\mathbb{R}^3$?
a) $\{(1,0,0),(0,1,0)\}$  
b) $\{(1,1,0),(0,1,1),(1,0,1)\}$  
c) $\{(1,2,3),(2,4,6),(3,6,9)\}$  
d) $\{(0,0,0),(1,0,0),(0,1,0)\}$  


HARD (Q24–Q30)
------------------------------------------------------------

Q24. (Problem-solving)
Let
$$
F = \begin{bmatrix}
1 & 2 & 3 \\
0 & 2 & 4 \\
0 & 0 & 0
\end{bmatrix}.
$$
Find $\dim(\text{Null}(F))$.
a) 0  
b) 1  
c) 2  
d) 3  


Q25. (Problem-solving)
Find whether the following vectors form a basis for the subspace
$$
S = \{(x,y,z) : x + y + z = 0\}.
$$
Vectors:
$$
u_1 = (1,-1,0),\quad
u_2 = (1,0,-1).
$$
a) Yes  
b) No  


Q26. (Problem-solving)
Let
$$
G = \begin{bmatrix}
1 & 0 & 1 \\
2 & 1 & 3 \\
0 & 1 & 1
\end{bmatrix}.
$$
Find $\dim(\text{Col}(G))$.
a) 1  
b) 2  
c) 3  
d) 0  


Q27. (Conceptual)
If rank$(A) = 1$ for a $3 \times 3$ matrix $A$, then:
a) $\dim(\text{Col}(A)) = 1$  
b) $\dim(\text{Null}(A)) = 1$  
c) $\dim(\text{Null}(A)) = 3$  
d) $\dim(\text{Col}(A)) = 0$  


Q28. (Problem-solving)
Let basis
$$
B = \left\{
\begin{bmatrix}1\\0\\0\end{bmatrix},
\begin{bmatrix}1\\1\\0\end{bmatrix},
\begin{bmatrix}0\\0\\1\end{bmatrix}
\right\}.
$$
Find the coordinate vector of  
$v = \begin{bmatrix}4\\3\\1\end{bmatrix}$ relative to $B$.
a)
$\begin{bmatrix}1\\3\\1\end{bmatrix}$  
b)
$\begin{bmatrix}4\\-1\\1\end{bmatrix}$  
c)
$\begin{bmatrix}3\\1\\1\end{bmatrix}$  
d)
$\begin{bmatrix}2\\2\\1\end{bmatrix}$  


Q29. (Problem-solving)
Find $\dim(\text{Null}(H))$ for
$$
H = \begin{bmatrix}
1 & 2 & 3 \\
0 & 1 & 4 \\
0 & 0 & 1
\end{bmatrix}.
$$
a) 0  
b) 1  
c) 2  
d) 3  


Q30. (Problem-solving)
Find a basis for the column space of
$$
J = \begin{bmatrix}
1 & 2 & 3 \\
1 & 2 & 3 \\
0 & 1 & 1
\end{bmatrix}.
$$
Which option contains the correct dimension?
a) $\dim(\text{Col}(J)) = 1$  
b) $\dim(\text{Col}(J)) = 2$  
c) $\dim(\text{Col}(J)) = 3$  
d) $\dim(\text{Col}(J)) = 0$  

------------------------------------------------------------
END OF QUESTIONS
------------------------------------------------------------

PRACTICE SHEET – LECTURE 6
Answer Key (with sanity check notes)

Q1   b  
Q2   a  
Q3   b  
Q4   b  
Q5   a  
Q6   a  
Q7   b  
Q8   c  

Q9   c  
Q10  c  
Q11  c  
Q12  b  
Q13  b  
Q14  b  
Q15  b  
Q16  b  
Q17  b  

Q18  mathematically: a, b, c, d are ALL in Col(D)  
Q19  c  

Q20  c  
Q21  b  
Q22  b  
Q23  b  

Q24  b  
Q25  a  
Q26  b  
Q27  a  
Q28  a  
Q29  a  
Q30  b



FULL SOLUTIONS (Q1–Q30)
------------------------------------------------------------
Q1. Definition of linear independence
------------------------------------------------------------
We say vectors v₁,…,vₖ are linearly independent if
    c₁ v₁ + … + cₖ vₖ = 0
implies
    c₁ = … = cₖ = 0
is the only solution.

Option b states exactly this.

Answer: b


------------------------------------------------------------
Q2. Definition of linear dependence
------------------------------------------------------------
A set is linearly dependent if at least one vector can be written as a linear combination of the others.

That’s precisely option a.

Answer: a


------------------------------------------------------------
Q3. Definition of a basis
------------------------------------------------------------
A basis of a vector space V is a set of vectors that is:
1. Linearly independent
2. Spans V

Option b says “independent vectors that span the space”.

Answer: b


------------------------------------------------------------
Q4. Dimension of a subspace
------------------------------------------------------------
Dimension is defined as the maximum number of linearly independent vectors in the subspace.

Option b matches this.

Answer: b


------------------------------------------------------------
Q5. Three independent vectors in R³
------------------------------------------------------------
In ℝ³:
- If three vectors are linearly independent, they span ℝ³.
- They don’t need to be orthogonal, and determinant “positive” is irrelevant wording.

So they form a basis of ℝ³.

Answer: a


------------------------------------------------------------
Q6. Independence of two vectors
------------------------------------------------------------
v₁ = (1,0,1), v₂ = (2,1,3).

Two vectors are dependent iff one is a scalar multiple of the other.

Check ratios:
- To have v₂ = k v₁, we’d need 2 = k·1 ⇒ k=2.
- Then we’d need 1 = k·0 ⇒ 1 = 2·0 = 0, impossible.

So no scalar k exists ⇒ they’re independent.

Answer: a


------------------------------------------------------------
Q7. Three multiples in a plane
------------------------------------------------------------
v₁ = (1,2,0), v₂ = (2,4,0), v₃ = (3,6,0).

Clearly v₂ = 2v₁ and v₃ = 3v₁. All lie on the same line.

Any set containing multiples is linearly dependent.

Answer: b


------------------------------------------------------------
Q8. How many independent vectors in n-dim?
------------------------------------------------------------
In an n-dimensional vector space, you can’t have more than n linearly independent vectors.

So for k independent vectors, we must have k ≤ n.

Answer: c


============================================================
Q9–Q23 (MEDIUM)
============================================================

------------------------------------------------------------
Q9. Pivot columns of A
------------------------------------------------------------
A =
[1 2 3]
[0 1 1]
[0 0 1]

This is already upper-triangular with nonzero diagonal entries in all 3 columns.

Pivot positions: (1,1), (2,2), (3,3) ⇒ 3 pivot columns.

Answer: c


------------------------------------------------------------
Q10. Rank of A
------------------------------------------------------------
Same A as Q9. Number of pivot columns = rank.

We found 3 pivots ⇒ rank(A) = 3.

Answer: c


------------------------------------------------------------
Q11. Rank of B
------------------------------------------------------------
B =
[1 2  1]
[0 1 -1]
[0 0  0]

Row-echelon form already:
- Non-zero rows: row1, row2
- So rank(B) = 2.

Answer: c


------------------------------------------------------------
Q12. Nullity of B
------------------------------------------------------------
B is 3×3 with rank 2.

Rank–nullity:
    rank(B) + dim(Null(B)) = n = 3
⇒ 2 + dim(Null(B)) = 3
⇒ dim(Null(B)) = 1.

Answer: b


------------------------------------------------------------
Q13. Independence of given 3 vectors
------------------------------------------------------------
v₁ = (1,1,0), v₂ = (2,0,1), v₃ = (3,1,1).

Form matrix with these as columns and compute rank:

M = [1 2 3
     1 0 1
     0 1 1]

You can check:
- Row-reduce or note: v₃ = v₁ + v₂.

Indeed, v₁ + v₂ = (1+2, 1+0, 0+1) = (3,1,1) = v₃.

So one is a linear combination of others ⇒ linearly dependent.

Answer: b


------------------------------------------------------------
Q14. Dimension of Col(C)
------------------------------------------------------------
C =
[1 2 3]
[1 2 3]
[0 1 1]

Row-reduce quickly:

R2 := R2 – R1 → 
[1 2 3]
[0 0 0]
[0 1 1]

Swap R2 and R3:
[1 2 3]
[0 1 1]
[0 0 0]

Non-zero rows: 2 ⇒ rank(C) = 2 ⇒ dim(Col(C)) = 2.

Answer: b


------------------------------------------------------------
Q15. Nullity of C
------------------------------------------------------------
C is 3×3 and rank(C) = 2.

Rank–nullity:
rank + nullity = n = 3 ⇒ 2 + nullity = 3 ⇒ nullity = 1.

Answer: b


------------------------------------------------------------
Q16. Basis for Null(A)
------------------------------------------------------------
A basis for the null space is formed by the “special solutions” corresponding to free variables in the homogeneous system. These are not pivot columns, but vectors built from free-variable choices.

So it consists of free-variable vectors.

Answer: b


------------------------------------------------------------
Q17. 3 vectors in R³ that span R³
------------------------------------------------------------
If 3 vectors in ℝ³ span ℝ³, then the span has dimension 3. A spanning set of exactly 3 vectors in a 3-dimensional space must be linearly independent (otherwise dimension < 3).

So they are linearly independent.

Answer: b


------------------------------------------------------------
Q18. Which vectors are in Col(D)?
------------------------------------------------------------
D =
[1 2 1]
[0 1 1]
[0 0 1]

Upper-triangular with diagonal entries 1,1,1 ⇒ det(D) = 1 ⇒ D is invertible.

If D is invertible, its column space is all of ℝ³. Therefore, **every** vector in ℝ³ is in Col(D).

So all options (a), (b), (c), (d) belong to Col(D).

Answer: a, b, c, d  (multi-correct as you specified)


------------------------------------------------------------
Q19. Coordinates of v relative to basis B
------------------------------------------------------------
Basis
b₁ = (1,0,1), b₂ = (0,1,1), b₃ = (1,1,0),
v = (3,2,1).

We want scalars a, b, c such that:
    a b₁ + b b₂ + c b₃ = v

Compute:

a(1,0,1) + b(0,1,1) + c(1,1,0)
= (a + c, b + c, a + b)
= (3,2,1)

So:
1) a + c = 3  
2) b + c = 2  
3) a + b = 1  

From 3): b = 1 − a.  
From 2): (1 − a) + c = 2 ⇒ c = 1 + a.  
From 1): a + (1 + a) = 3 ⇒ 2a + 1 = 3 ⇒ 2a = 2 ⇒ a = 1.

Then:
b = 1 − 1 = 0  
c = 1 + 1 = 2  

So coordinate vector is
[v]ᵦ = [1, 0, 2]ᵀ.

You’ve updated option c to be this vector, so:

Answer: c


------------------------------------------------------------
Q20. Rank of E
------------------------------------------------------------
E =
[1 0  2]
[0 1 -1]
[0 0  0]

Non-zero rows: 2 ⇒ rank(E) = 2.

Answer: c


------------------------------------------------------------
Q21. Nullity of E
------------------------------------------------------------
E is 3×3, rank(E)=2.

Rank–nullity:
2 + nullity = 3 ⇒ nullity = 1.

Answer: b


------------------------------------------------------------
Q22. Dimension theorem
------------------------------------------------------------
For an m×n matrix A, the dimension theorem says:
    dim(Col(A)) + dim(Null(A)) = n

Option b is exactly that.

Answer: b


------------------------------------------------------------
Q23. Basis for R³
------------------------------------------------------------
Check each set:

a) {(1,0,0),(0,1,0)} → only 2 vectors. Can’t span ℝ³. Not a basis.

b) {(1,1,0),(0,1,1),(1,0,1)} → 3 vectors. Check independence:

Form matrix M with these as columns:
[1 0 1
 1 1 0
 0 1 1]

Compute rank: you can row-reduce; you’ll get rank 3. So independent and span ℝ³ ⇒ basis.

c) (1,2,3), (2,4,6), (3,6,9): they’re multiples of each other ⇒ rank 1 ⇒ not a basis.

d) Includes (0,0,0): any set containing zero vector is automatically dependent ⇒ not a basis.

Answer: b


============================================================
Q24–Q30 (HARD)
============================================================

------------------------------------------------------------
Q24. Nullity of F
------------------------------------------------------------
F =
[1 2 3]
[0 2 4]
[0 0 0]

Non-zero rows: row1, row2 ⇒ rank(F) = 2. Matrix is 3×3 ⇒

nullity = 3 − 2 = 1.

Answer: b


------------------------------------------------------------
Q25. Basis for S = {(x,y,z): x + y + z = 0}
------------------------------------------------------------
Subspace S: plane through origin.

Given u₁ = (1,−1,0), u₂ = (1,0,−1).

Check they lie in S:
- For u₁: 1 + (−1) + 0 = 0 ✔
- For u₂: 1 + 0 + (−1) = 0 ✔

Check independence: if
    α u₁ + β u₂ = 0,

then:
α(1,−1,0) + β(1,0,−1) = (0,0,0)
⇒ (α + β, −α, −β) = (0,0,0)
So:
- −α = 0 ⇒ α = 0
- −β = 0 ⇒ β = 0

Thus only trivial combination ⇒ independent.

Plane S has dimension 2, and we have 2 independent vectors in S ⇒ they form a basis.

Answer: a


------------------------------------------------------------
Q26. Dimension of Col(G)
------------------------------------------------------------
G =
[1 0 1]
[2 1 3]
[0 1 1]

Row-reduce:

Start:
[1 0 1]
[2 1 3]
[0 1 1]

R2 := R2 − 2R1 → [2−2*1, 1−0, 3−2] = [0,1,1]:

Now:
[1 0 1]
[0 1 1]
[0 1 1]

R3 := R3 − R2 → [0,0,0].

Non-zero rows: 2 ⇒ rank(G) = 2 ⇒ dim(Col(G)) = 2.

Answer: b


------------------------------------------------------------
Q27. Rank 1 for 3×3 matrix
------------------------------------------------------------
If rank(A) = 1 for a 3×3:

- Column space dimension = rank(A) = 1
- Nullity = 3 − 1 = 2 (not 1, not 3)
- So dim(Col(A)) = 1 is the correct statement.

Answer: a


------------------------------------------------------------
Q28. Coordinates of v wrt basis B
------------------------------------------------------------
Basis
b₁ = (1,0,0), b₂ = (1,1,0), b₃ = (0,0,1),
v = (4,3,1).

We want a,b,c such that:
a b₁ + b b₂ + c b₃ = v
⇒ a(1,0,0) + b(1,1,0) + c(0,0,1)
= (a + b, b, c) = (4,3,1).

So:
1) a + b = 4  
2) b = 3  
3) c = 1  

From 2): b = 3.  
Then 1): a + 3 = 4 ⇒ a = 1.  
c = 1.

So [v]ᵦ = [1,3,1]ᵀ.

Matches option a.

Answer: a


------------------------------------------------------------
Q29. Nullity of H
------------------------------------------------------------
H =
[1 2 3]
[0 1 4]
[0 0 1]

Upper triangular with non-zero diagonal ⇒ rank(H) = 3.

3×3 matrix ⇒ nullity = 3 − 3 = 0.

Answer: a


------------------------------------------------------------
Q30. Dimension of Col(J)
------------------------------------------------------------
J =
[1 2 3]
[1 2 3]
[0 1 1]

We already row-reduced J in earlier problems (same as C):

Row-reduction gives 2 non-zero rows ⇒ rank(J) = 2 ⇒ dim(Col(J)) = 2.

Answer: b


============================================================
END OF SOLUTIONS
============================================================
