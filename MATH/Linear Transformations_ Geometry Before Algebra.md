---
title: 'Linear Transformations: Geometry Before Algebra'

---

PRACTICE SHEET – LECTURE 3
Linear Transformations: Geometry Before Algebra
30 Questions | 8 Easy – 15 Medium – 7 Hard | MCQ | Answers + Solutions at end

Topics covered:
Matrices as transformations • Columns as images of basis vectors • Rotation • Reflection • Scaling • Shear • Identity & inverse (geometric view) • Determinant as area-scaling intuition


------------------------------------------------------------
EASY (8 questions)
------------------------------------------------------------

Q1. (Conceptual, Single-correct)
A linear transformation $T$ is fully determined by:
a) Its action on infinitely many vectors
b) Its action on the standard basis vectors
c) Its action on any random unit vector
d) Its action only on the zero vector

Q2. (Conceptual, Single-correct)
If $T$ is represented by matrix $A$, then $T(x)$ equals:
a) $Ax$
b) $A + x$
c) $xA$
d) $A - x$

Q3. (Conceptual, Single-correct)
Which matrix represents the **identity transformation**?
a)
$$
\begin{bmatrix}
2 & 0 \\
0 & 2
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
0 & -1 \\
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

Q4. (Conceptual, Single-correct)
A **scaling** transformation:
a) Changes orientation only
b) Changes magnitude but not direction (except sign flips)
c) Changes basis vectors but keeps length same
d) Only rotates vectors

Q5. (Conceptual, Single-correct)
The determinant of a transformation matrix in $\mathbb{R}^2$ represents:
a) Area-scaling factor
b) Perimeter-scaling factor
c) Volume-scaling factor
d) Number of fixed points

Q6. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
2 & 0 \\
0 & 3
\end{bmatrix}
$$
Then the image of $e_2$ under $A$ is:
a) $(1, 0)$
b) $(0, 1)$
c) $(2, 0)$
d) $(0, 3)$

Q7. (Conceptual, Single-correct)
A transformation that **flips** vectors across the x-axis is a:
a) Rotation
b) Reflection
c) Shear
d) Projection

Q8. (Conceptual, Single-correct)
The linear transformation represented by $A$ maps basis vectors to:
a) The eigenvectors of $A$
b) The columns of $A$
c) Random points
d) The rows of $A$


------------------------------------------------------------
MEDIUM (15 questions)
------------------------------------------------------------

Q9. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
0 & -1 \\
1 & 0
\end{bmatrix}
$$
This matrix corresponds to a rotation of:
a) 90° clockwise  
b) 90° counterclockwise  
c) 180°  
d) 270° clockwise

Q10. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & k \\
0 & 1
\end{bmatrix}
$$
This matrix represents:
a) Scaling
b) Reflection
c) Shear
d) Rotation

Q11. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{bmatrix}
$$
Then $A$ represents:
a) Rotation by $\theta$
b) Rotation by $-\theta$
c) Reflection across x-axis
d) Scaling by $\cos\theta$

Q12. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
$$
This represents:
a) Reflection across y-axis  
b) Reflection across x-axis  
c) 180° rotation  
d) Shear

Q13. (Problem-solving, Multi-correct)
Which matrices below **preserve orientation** (determinant > 0)?
a)
$$
\begin{bmatrix}
0 & -1 \\
1 &  0
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
-1 & 0 \\
0  & -1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
2 & 0 \\
0 & 2
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
1 & 1 \\
0 & 1
\end{bmatrix}
$$

Q14. (Problem-solving, Single-correct)
Compute $\det A$ for
$$
A = \begin{bmatrix}
3 & 2 \\
4 & 1
\end{bmatrix}
$$
a) 10
b) −10
c) −5
d) 5

Q15. (Problem-solving, Single-correct)
If $\det(A) = 0$, then the transformation:
a) Is invertible  
b) Squashes area to zero  
c) Preserves area  
d) Always scales area by 1

Q16. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
1 & 2 \\
0 & 1
\end{bmatrix},
\quad
x = \begin{bmatrix}
3 \\
1
\end{bmatrix}
$$
Compute $Ax$.
a)
$$
\begin{bmatrix}
5 \\
1
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
4 \\
1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
5 \\
3
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
3 \\
1
\end{bmatrix}
$$

Q17. (Problem-solving, Single-correct)
For
$$
A = \begin{bmatrix}
2 & 0 \\
0 & 2
\end{bmatrix}
$$
The transformation:
a) Doubles length of every vector  
b) Preserves length  
c) Halves length  
d) Rotates vectors

Q18. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
0 & 1 \\
1 & 0
\end{bmatrix}
$$
This represents:
a) Swap of coordinates
b) Reflection across y=x
c) Both a and b (they are equivalent)
d) Projection onto y = x

Q19. (Problem-solving, Multi-correct)
Which of the following matrices **do not change the area** of shapes in $\mathbb{R}^2$ (i.e., $|\det(A)| = 1$)?
a)
$$
\begin{bmatrix}
0 & -1 \\
1 &  0
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
2 & 0 \\
0 & 1
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
$$

Q20. (Conceptual, Single-correct)
If $A$ is invertible, the transformation $T(x)=Ax$:
a) Collapses dimension
b) Preserves one-to-one mapping
c) Sends every vector to zero
d) Is not linear

Q21. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
0 & -1 \\
1 &  0
\end{bmatrix}
$$
Compute $\det(A)$.
a) −1
b) 0
c) 1
d) 2

Q22. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
4 & 0 \\
0 & 3
\end{bmatrix}
$$
The transformation scales area by:
a) 12
b) 7
c) 4
d) 3

Q23. (Conceptual, Multi-correct)
Which transformations leave the **origin** fixed?
a) Rotations
b) Scaling
c) Shears
d) Translations


------------------------------------------------------------
HARD (7 questions)
------------------------------------------------------------

Q24. (Problem-solving, Multi-correct)
Which matrices **have an inverse**?
a)
$$
\begin{bmatrix}
2 & 0 \\
0 & 3
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1 & 1 \\
0 & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
2 & 4 \\
1 & 2
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
0 & 1 \\
0 & 0
\end{bmatrix}
$$

Q25. (Problem-solving, Single-correct)
Which reflection matrix flips points across the **y-axis**?
a)
$$
\begin{bmatrix}
1 & 0 \\
0 & 1
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
-1 & 0 \\
0  & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
1 & 0 \\
0 & -1
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
0 & -1 \\
1 &  0
\end{bmatrix}
$$

Q26. (Problem-solving, Single-correct)
For
$$
A = \begin{bmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta
\end{bmatrix}
$$
its inverse is:
a) $A$
b)
$$
\begin{bmatrix}
\cos\theta & \sin\theta \\
-\sin\theta & \cos\theta
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & -\cos\theta
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
\cos(-\theta) & -\sin(-\theta) \\
\sin(-\theta) & \cos(-\theta)
\end{bmatrix}
$$

Q27. (Conceptual, Single-correct)
If $\det(A) < 0$, the transformation:
a) Preserves orientation
b) Reverses orientation
c) Eliminates dimension
d) Has infinite fixed points

Q28. (Problem-solving, Single-correct)
Let
$$
A = \begin{bmatrix}
0 & 2 \\
-2 & 0
\end{bmatrix}
$$
This transformation equals rotation by:
a) 90° clockwise and scaling by 2
b) 90° counterclockwise and scaling by 2
c) 180°
d) Shear

Q29. (Problem-solving, Multi-correct)
Which matrices **map some non-zero vector to the zero vector**?
a)
$$
\begin{bmatrix}
2 & 0 \\
0 & 3
\end{bmatrix}
$$
b)
$$
\begin{bmatrix}
1 & 1 \\
0 & 1
\end{bmatrix}
$$
c)
$$
\begin{bmatrix}
2 & 4 \\
1 & 2
\end{bmatrix}
$$
d)
$$
\begin{bmatrix}
0 & 1 \\
0 & 0
\end{bmatrix}
$$

Q30. (Conceptual, Multi-correct)
Which statements are TRUE?
a) Columns of a transformation matrix show where basis vectors land
b) Determinant magnitude describes area scaling in $\mathbb{R}^2$
c) Determinant sign indicates whether orientation is preserved or reversed
d) Every matrix with non-zero determinant is a projection


------------------------------------------------------------
ANSWER KEY
------------------------------------------------------------
1 b
2 a
3 b
4 b
5 a
6 d
7 b
8 b

9 b
10 c
11 a
12 b
13 a, c, d
14 c
15 b
16 a
17 a
18 c
19 a, b, d
20 b
21 c
22 a
23 a, b, c

24 a, b
25 b
26 d
27 b
28 b
29 c, d
30 a, b, c


------------------------------------------------------------
STEP-BY-STEP SOLUTIONS
------------------------------------------------------------

Q1. A linear map is fixed by its action on basis → b  
Q2. $T(x) = Ax$ → a  
Q3. Identity matrix is $\begin{bmatrix}1&0\\0&1\end{bmatrix}$ → b  
Q4. Scaling changes magnitude only → b  
Q5. Determinant = area scaling → a  
Q6. Image of $e_2$ is column 2 → $(0,3)$ → d  
Q7. Flip across axis = reflection → b  
Q8. Columns of $A$ = images of basis vectors → b  

Q9. Standard CCW rotation by 90° → b  
Q10. Matrix with 1s on diagonal and upper entry = shear → c  
Q11. Classical rotation matrix → a  
Q12. Negates y-coordinate → reflection across x-axis → b  
Q13. det(a)=1, det(b)=1, det(c)=4, det(d)=1 → positive → a,c,d  
Q14. det = $3(1) - 2(4) = -5$ → c  
Q15. det 0 → collapses area → b  
Q16. $Ax = [1*3 + 2*1; 0*3 + 1*1] = [5; 1]$ → a  
Q17. Multiply norm by 2 everywhere → a  
Q18. Swap coordinates = reflection across $y=x$ = same as swap → c  
Q19. Determinant magnitude = 1 → a,b,d  
Q20. Invertible → one-to-one → b  
Q21. det = 1 → c  
Q22. Area scale = 4 * 3 = 12 → a  
Q23. All linear maps except translations fix origin → a,b,c  
Q24. Invertible matrices ⇔ det $\neq$ 0 → a (det=6), b (det=1), c (det=0), d (det=0) → a,b  
Q25. Reflection across y-axis = $\begin{bmatrix}-1&0\\0&1\end{bmatrix}$ → b  
Q26. Inverse rotation = rotation by −θ, i.e.
$\begin{bmatrix}\cos(-\theta)&-\sin(-\theta)\\\sin(-\theta)&\cos(-\theta)\end{bmatrix}$ → d  
Q27. det < 0 → reverses orientation → b  
Q28. Rotation by 90° CCW + scalar 2 → b  
Q29. Singular matrices send some non-zero vector to 0 → c,d  
Q30. All true except (d) — non-zero determinant matrices are not projections → a,b,c

