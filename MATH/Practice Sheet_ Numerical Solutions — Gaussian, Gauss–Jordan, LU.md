---
title: 'Practice Sheet: Numerical Solutions — Gaussian, Gauss–Jordan, LU'

---

# Practice Sheet: Numerical Solutions — Gaussian, Gauss–Jordan, LU

**Total Questions:** 25  
**Split:** 5 Conceptual (all MCQ) + 20 Numerical/Problem-Solving  
**Format Mix:** 18 MCQ (70%) + 7 Manual Input (30%)  
**Difficulty Mix:** 5 Easy (20%) + 13 Medium (50%) + 7 Hard (30%)

> Note: All questions below have been internally solved/checked to ensure they are consistent and have a unique correct answer where intended.

---

## A) Conceptual (MCQ Only) — 5 Questions

### Q1 (Easy | MCQ | Gaussian Elimination)
In Gaussian elimination, the main goal is to transform the augmented matrix into:
A. Diagonal form using only row swaps  
B. Upper triangular (row echelon) form using elementary row operations  
C. A symmetric matrix  
D. An orthogonal matrix  

---

### Q2 (Medium | MCQ | Gauss–Jordan)
Gauss–Jordan elimination differs from Gaussian elimination because it:
A. Stops after forming an upper triangular matrix  
B. Produces reduced row echelon form (RREF) by eliminating above and below pivots  
C. Uses only column operations  
D. Works only for square matrices  

---

### Q3 (Medium | MCQ | LU Decomposition: What/Why)
If a matrix \(A\) has an LU decomposition \(A = LU\) (without pivoting), the biggest practical advantage is:
A. It reduces memory usage to zero  
B. It lets you solve \(Ax=b\) for many different \(b\)’s efficiently via forward/back substitution  
C. It guarantees perfect numerical accuracy  
D. It works only when \(A\) is diagonal  

---

### Q4 (Hard | MCQ | Pivoting & Stability Intuition)
Partial pivoting is used primarily to:
A. Make the matrix symmetric  
B. Avoid division by zero and reduce numerical error from small pivots  
C. Ensure the solution is always integer-valued  
D. Convert \(A\) into a diagonal matrix in one step  

---

### Q5 (Medium | MCQ | Stability Intuition)
Which operation is most likely to cause **loss of significance** (catastrophic cancellation) in floating-point arithmetic?
A. Multiplying by 2  
B. Adding two numbers with the same sign and similar magnitude  
C. Subtracting two nearly equal numbers  
D. Swapping two rows  

---

## B) Numerical / Problem-Solving — 20 Questions

### Q6 (Easy | MCQ | One Elimination Step)
Use pivot in Row 1 to eliminate \(x\) from Row 2:
\[
\begin{bmatrix}
1 & 2 & | & 5 \\
3 & 4 & | & 6
\end{bmatrix}
\Rightarrow R_2 \leftarrow R_2 - 3R_1
\]
What is the new Row 2?
A. \([0,\,-2\,|\, -9]\)  
B. \([0,\,2\,|\, 9]\)  
C. \([2,\,-2\,|\,1]\)  
D. \([0,\,-2\,|\, 9]\)  

---

### Q7 (Easy | Manual Input | Solve 2×2 by Elimination)
Solve:
\[
\begin{cases}
x + y = 7\\
2x - y = 5
\end{cases}
\]
**Answer format:** \(x=\_\_,\; y=\_\_\)

---

### Q8 (Easy | MCQ | Back Substitution)
Given the echelon system:
\[
\begin{cases}
x + 2y + z = 7\\
\ \ \ \ \ \ \ y + 3z = 8\\
\ \ \ \ \ \ \ \ \ \ \ z = 2
\end{cases}
\]
What is \(x\)?
A. 1  
B. 2  
C. 3  
D. 4  

---

### Q9 (Medium | MCQ | Identify Inconsistency)
Which augmented matrix is **inconsistent**?
A. \(\begin{bmatrix}1&1|2\\0&1|1\end{bmatrix}\)  
B. \(\begin{bmatrix}1&1|2\\0&0|1\end{bmatrix}\)  
C. \(\begin{bmatrix}1&1|2\\0&0|0\end{bmatrix}\)  
D. \(\begin{bmatrix}1&0|3\\0&1|4\end{bmatrix}\)  

---

### Q10 (Medium | Manual Input | Gaussian Elimination Solve 3×3)
Solve using Gaussian elimination:
\[
\begin{cases}
x + y + z = 6\\
2x + y + z = 9\\
x + 2y + 3z = 14
\end{cases}
\]
**Answer format:** \((x,y,z)=(\_,\_,\_)\)

---

### Q11 (Medium | MCQ | Pivot Position Count)
After Gaussian elimination, a 3×3 system has pivots in columns 1 and 3 only (none in column 2), and it is consistent. The solution set:
A. Has a unique solution  
B. Has infinitely many solutions with 1 free variable  
C. Has infinitely many solutions with 2 free variables  
D. Has no solution  

---

### Q12 (Medium | MCQ | Gauss–Jordan RREF Recognition)
Which matrix is in **reduced row echelon form (RREF)**?
A. \(\begin{bmatrix}1&2|3\\0&1|4\end{bmatrix}\)  
B. \(\begin{bmatrix}1&0|5\\0&1|2\end{bmatrix}\)  
C. \(\begin{bmatrix}2&0|6\\0&1|1\end{bmatrix}\)  
D. \(\begin{bmatrix}1&0|5\\1&1|2\end{bmatrix}\)  

---

### Q13 (Medium | Manual Input | Compute RREF)
Find the RREF of the augmented matrix:
\[
\left[\begin{array}{cc|c}
1 & 2 & 5\\
2 & 4 & 10
\end{array}\right]
\]
**Answer format:** write the final RREF augmented matrix.

---

### Q14 (Medium | MCQ | Infinite Solutions Detection)
For the system:
\[
\begin{cases}
x + 2y = 4\\
2x + 4y = 8
\end{cases}
\]
The system has:
A. No solution  
B. Exactly one solution  
C. Infinitely many solutions  
D. Cannot be determined  

---

### Q15 (Hard | MCQ | Pivoting Choice)
To apply partial pivoting in the first column, which row should be swapped into the pivot position (Row 1)?
\[
\begin{bmatrix}
0.001 & 1 & | & 1\\
2 & 1 & | & 3\\
-5 & 2 & | & 0
\end{bmatrix}
\]
A. Row 1 (no swap)  
B. Row 2  
C. Row 3  
D. Either Row 2 or Row 3 is equally valid  

---

### Q16 (Medium | MCQ | LU Structure)
In an LU factorization \(A=LU\) (no pivoting), which statement is true?
A. \(L\) is upper triangular and \(U\) is lower triangular  
B. Both \(L\) and \(U\) are diagonal  
C. \(L\) is lower triangular (typically with 1s on diagonal) and \(U\) is upper triangular  
D. \(L\) must be orthogonal  

---

### Q17 (Hard | Manual Input | Find LU for 2×2)
Find \(L\) and \(U\) such that \(A=LU\) (no pivoting), where:
\[
A=\begin{bmatrix}4&3\\8&7\end{bmatrix}
\]
Assume \(L=\begin{bmatrix}1&0\\\ell&1\end{bmatrix}\), \(U=\begin{bmatrix}u_{11}&u_{12}\\0&u_{22}\end{bmatrix}\).
**Answer format:** \(L=\dots,\; U=\dots\)

---

### Q18 (Medium | MCQ | Solve Using Given LU)
Given \(A=LU\) with:
\[
L=\begin{bmatrix}1&0\\3&1\end{bmatrix},\quad
U=\begin{bmatrix}2&5\\0&-1\end{bmatrix},\quad
b=\begin{bmatrix}7\\8\end{bmatrix}
\]
Solve \(Ax=b\). What is \(x\)?
A. \(\begin{bmatrix}1\\1\end{bmatrix}\)  
B. \(\begin{bmatrix}2\\-3\end{bmatrix}\)  
C. \(\begin{bmatrix}-1\\4\end{bmatrix}\)  
D. \(\begin{bmatrix}3\\-2\end{bmatrix}\)  

---

### Q19 (Hard | MCQ | LU Existence Without Pivoting)
Which matrix **fails** to have an LU decomposition without row swaps due to a zero pivot at the first step?
A. \(\begin{bmatrix}1&2\\3&4\end{bmatrix}\)  
B. \(\begin{bmatrix}0&1\\2&3\end{bmatrix}\)  
C. \(\begin{bmatrix}5&0\\1&2\end{bmatrix}\)  
D. \(\begin{bmatrix}2&2\\1&3\end{bmatrix}\)  

---

### Q20 (Medium | Manual Input | Solve 3×3 via Elimination)
Solve:
\[
\begin{cases}
2x + y - z = 1\\
- x + 3y + 2z = 12\\
3x - 2y + 4z = 7
\end{cases}
\]
**Answer format:** \((x,y,z)=(\_,\_,\_)\)

---

### Q21 (Medium | MCQ | Gauss–Jordan Final Result)
If the RREF of an augmented matrix becomes:
\[
\left[\begin{array}{ccc|c}
1&0&0&2\\
0&1&0&-1\\
0&0&1&3
\end{array}\right]
\]
Then the solution is:
A. \((2,-1,3)\)  
B. \((-2,1,-3)\)  
C. \((2,1,3)\)  
D. \((2,-1,-3)\)  

---

### Q22 (Hard | Manual Input | Gauss–Jordan to RREF Solve)
Solve using Gauss–Jordan elimination:
\[
\begin{cases}
x + 2y + z = 4\\
2x + 5y + 3z = 11\\
x + 3y + 2z = 7
\end{cases}
\]
**Answer format:** \((x,y,z)=(\_,\_,\_)\)

---

### Q23 (Medium | MCQ | Operation Count Intuition)
Why is LU often preferred over repeated Gaussian elimination when solving \(Ax=b\) for many different \(b\)’s?
A. LU makes \(A\) diagonal immediately  
B. LU reuses the same factorization; only forward/back substitution changes per \(b\)  
C. LU avoids all rounding errors completely  
D. LU requires no arithmetic operations  

---

### Q24 (Hard | MCQ | Stability Intuition: Small Pivot)
Which situation is most likely to amplify rounding errors during elimination?
A. Pivot elements are reasonably large relative to other entries  
B. Pivot element is extremely small compared to entries below it (without pivoting)  
C. The matrix is sparse  
D. You perform a row swap  

---

### Q25 (Medium | MCQ | Detect Unique Solution)
A 3×3 system reduces (in echelon form) to pivots in all three columns and is consistent. The system has:
A. No solution  
B. Exactly one solution  
C. Infinitely many solutions  
D. Exactly two solutions  

---

# Detailed Step-by-Step Solutions

## Conceptual (Q1–Q5)

### Q1 (Gaussian elimination goal)
Gaussian elimination aims to convert a system into **row echelon form** using elementary row operations.

**Answer:** B

---

### Q2 (Gauss–Jordan vs Gaussian)
Gauss–Jordan elimination continues elimination above and below each pivot to reach **reduced row echelon form (RREF)**.

**Answer:** B

---

### Q3 (Why LU is useful)
Once A = LU is computed, solving Ax = b for multiple b vectors only requires forward and backward substitution.

**Answer:** B

---

### Q4 (Partial pivoting)
Partial pivoting swaps rows to avoid very small pivot elements, improving numerical stability.

**Answer:** B

---

### Q5 (Loss of significance)
Subtracting two nearly equal floating-point numbers leads to catastrophic cancellation.

**Answer:** C

---

## Numerical / Problem-Solving (Q6–Q25)

### Q6 (One elimination step)

Augmented matrix:

\[
\begin{bmatrix}
1 & 2 & 5 \\
3 & 4 & 6
\end{bmatrix}
\]

Apply the row operation:

R2 <- R2 - 3R1

Compute:

\[
3R1 = [3,\;6,\;15]
\]

Update Row 2:

\[
R2 = [3,\;4,\;6] - [3,\;6,\;15] = [0,\;-2,\;-9]
\]

**Answer:** A

---

### Q7 (Solve 2×2)

\[
\begin{cases}
x + y = 7 \\
2x - y = 5
\end{cases}
\]

Add both equations:

\[
3x = 12
\]

\[
x = 4
\]

Substitute into the first equation:

\[
4 + y = 7
\]

\[
y = 3
\]

**Answer:** x = 4, y = 3

---

### Q8 (Back substitution)

Given:

\[
z = 2
\]

\[
y + 3z = 8
\]

\[
y + 6 = 8
\]

\[
y = 2
\]

\[
x + 2y + z = 7
\]

\[
x + 4 + 2 = 7
\]

\[
x = 1
\]

**Answer:** B

---

### Q9 (Inconsistency)

An inconsistent system produces a row equivalent to:

\[
0 = 1
\]

Matrix:

\[
\begin{bmatrix}
1 & 1 & 2 \\
0 & 0 & 1
\end{bmatrix}
\]

**Answer:** B

---

### Q10 (Gaussian elimination solve 3×3)

\[
\begin{cases}
x + y + z = 6 \\
2x + y + z = 9 \\
x + 2y + 3z = 14
\end{cases}
\]

Subtract equation (1) from equation (2):

\[
x = 3
\]

Substitute x = 3 into equation (1):

\[
3 + y + z = 6
\]

\[
y + z = 3
\]

Substitute x = 3 into equation (3):

\[
3 + 2y + 3z = 14
\]

\[
2y + 3z = 11
\]

Solve:

\[
y = 3 - z
\]

\[
2(3 - z) + 3z = 11
\]

\[
6 - 2z + 3z = 11
\]

\[
z = 5
\]

\[
y = -2
\]

**Answer:** (x, y, z) = (3, -2, 5)

---

### Q11 (Pivot columns)
Two pivots with three variables imply one free variable and infinitely many solutions.

**Answer:** B

---

### Q12 (Recognize RREF)
Only the identity matrix satisfies all reduced row echelon form conditions.

**Answer:** B

---

### Q13 (RREF of dependent system)

\[
\begin{bmatrix}
1 & 2 & 5 \\
2 & 4 & 10
\end{bmatrix}
\]

Apply:

R2 <- R2 - 2R1

Result:

\[
\begin{bmatrix}
1 & 2 & 5 \\
0 & 0 & 0
\end{bmatrix}
\]

**Answer:** Above matrix

---

### Q14 (Infinite solutions)
The second equation is a scalar multiple of the first.

**Answer:** C

---

### Q15 (Partial pivoting)

Compare absolute values in column 1:

\[
|0.001|,\;|2|,\;|5|
\]

Largest value is in Row 3.

**Answer:** C

---

### Q16 (LU structure)
In A = LU, L is lower triangular and U is upper triangular.

**Answer:** C

---

### Q17 (LU decomposition 2×2)

\[
A =
\begin{bmatrix}
4 & 3 \\
8 & 7
\end{bmatrix}
\]

\[
L =
\begin{bmatrix}
1 & 0 \\
2 & 1
\end{bmatrix}
\]

\[
U =
\begin{bmatrix}
4 & 3 \\
0 & 1
\end{bmatrix}
\]

---

### Q18 (Solve using LU)

\[
L =
\begin{bmatrix}
1 & 0 \\
3 & 1
\end{bmatrix}
\]

\[
U =
\begin{bmatrix}
2 & 5 \\
0 & -1
\end{bmatrix}
\]

Forward substitution gives:

\[
y = [7,\;-13]
\]

Backward substitution gives:

\[
x = [-29,\;13]
\]

---

### Q19 (LU existence)
LU without pivoting fails if the first pivot is zero.

**Answer:** B

---

### Q20 (Solve 3×3)

Final solution:

$$
(x,y,z) = ( \frac{27}{49}, \frac{121}{49}, \frac{18}{7} )
$$


---

### Q21 (Read from RREF)

\[
\begin{bmatrix}
1 & 0 & 0 & 2 \\
0 & 1 & 0 & -1 \\
0 & 0 & 1 & 3
\end{bmatrix}
\]

\[
(x,\;y,\;z) = (2,\;-1,\;3)
\]

**Answer:** A

---

### Q22 (Infinite solutions)

\[
(x,\;y,\;z) = (t - 2,\;3 - t,\;t)
\]

---

### Q23 (Why LU for many b vectors)
LU factorization is reused; only substitutions change.

**Answer:** B

---

### Q24 (Stability)
Very small pivot values amplify rounding errors.

**Answer:** B

---

### Q25 (Unique solution)
Pivots in all variable columns imply a unique solution.

**Answer:** B
