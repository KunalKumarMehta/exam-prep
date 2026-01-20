---
title: 'RREF, Pivot Columns, Rank–Nullity, Systems'

---

PRACTICE SHEET – LECTURE 8
RREF, Pivot Columns, Rank–Nullity, Systems
(QUESTIONS ONLY — 30 MCQs)

------------------------------------------------------------
EASY (Q1–Q8)
------------------------------------------------------------

Q1. (Conceptual)
RREF requires all pivot positions to contain:
a) Any non-zero number  
b) Only 1  
c) The same value  
d) Zero  

Q2. (Conceptual)
A pivot column is:
a) Any column with zeros  
b) A column containing a leading 1 in RREF  
c) A column containing only ones  
d) A column with the largest entry  

Q3. (Conceptual)
Rank(A) equals:
a) Number of rows of A  
b) Number of pivot columns  
c) Number of non-zero entries  
d) Number of columns of A  

Q4. (Conceptual)
Null space of A is:
a) All x such that Ax = b  
b) All x such that Ax = 0  
c) All linear combinations of rows of A  
d) All linear combinations of columns of A  

Q5. (Conceptual)
An overdetermined system has:
a) More variables than equations  
b) More equations than variables  
c) Equal equations and variables  
d) Rank = 0  

Q6. (Conceptual)
If A is 3×3 and rank(A)=3, then:
a) Null space = {0}  
b) Null space has dimension 1  
c) Infinite solutions to Ax=0  
d) A must have a zero row  

Q7. (Problem-solving)
Given:
[1 0 | 2]
[0 1 | 3]
This system:
a) Has unique solution  
b) Has infinite solutions  
c) Has no solution  
d) Cannot be determined  

Q8. (Conceptual)
Rank-nullity theorem states:
a) rank(A) + nullity(A) = m  
b) rank(A) + nullity(A) = n  
c) rank(A) = nullity(A)  
d) rank(A)*nullity(A) = n  

------------------------------------------------------------
MEDIUM (Q9–Q23)
------------------------------------------------------------

Q9. (Problem-solving)
Compute rank of:
A =
[1 2 3]
[2 4 6]
[0 1 1]
a) 1  
b) 2  
c) 3  
d) 0  

Q10. (Problem-solving)
Find pivot columns of:
A =
[1 2 1]
[0 1 1]
[0 0 1]
a) 1,2  
b) 1,2,3  
c) 2,3  
d) 1 only  

Q11. (Problem-solving)
For matrix in Q10, nullity(A) =
a) 0  
b) 1  
c) 2  
d) 3  

Q12. (Problem-solving)
Solve Ax = 0 for:
A =
[1 2 1]
[0 1 1]
[0 0 0]
Number of free variables?
a) 0  
b) 1  
c) 2  
d) 3  

Q13. (Problem-solving)
Let
A =
[1 1 0]
[2 2 0]
[0 0 1]
Rank(A) =
a) 1  
b) 2  
c) 3  
d) 0  

Q14. (Problem-solving)
Let A be 3×3 with rank 2. Then nullity =
a) 0  
b) 1  
c) 2  
d) 3  

Q15. (Problem-solving)
Determine consistency:
[1 2 1 | 4]
[0 1 1 | 2]
[0 0 0 | 5]
a) Consistent  
b) Inconsistent  

Q16. (Problem-solving)
Convert to RREF:
[1 2 | 3]
[2 4 | 6]
a)
[1 2 | 3]
[0 0 | 0]  
b)
[1 0 | 1]  
[0 1 | 1]  
c)
[1 2 | 3]
[0 1 | 2]  
d) None  

Q17. (Conceptual)
If A is 4×3 with rank 3, system Ax=b:
a) Always consistent  
b) Always inconsistent  
c) Consistent only if b ∈ Col(A)  
d) Always infinite solutions  

Q18. (Problem-solving)
Let  
A =
[1 0 2]
[0 1 -1]
[0 0 0], b=[3;2;5].
Is the system consistent?
a) Yes  
b) No  

Q19. (Problem-solving)
Find rank of:
[1 1 1]
[3 3 3]
[1 1 1]
a) 1  
b) 2  
c) 3  
d) 0  

Q20. (Problem-solving)
Ax = 0 has infinitely many solutions when:
a) rank(A)=n  
b) rank(A)<n  
c) rank(A)=0  
d) A is invertible  

Q21. (Problem-solving)
Let A be 5×3 with rank 2. Nullity(A)=?
a) 0  
b) 1  
c) 2  
d) 3  

Q22. (Problem-solving)
Which system is underdetermined?
a) 3 equations, 5 variables  
b) 5 equations, 3 variables  
c) 3 equations, 3 variables  
d) 2 equations, 2 variables  

Q23. (Conceptual)
If an RREF matrix has 2 pivot columns and 4 total columns, then:
a) nullity = 1  
b) nullity = 2  
c) nullity = 3  
d) nullity = 4  

------------------------------------------------------------
HARD (Q24–Q30)
------------------------------------------------------------

Q24. (Problem-solving)
Find number of solutions:
[1 2 1 | 3]
[2 4 2 | 6]
[0 1 1 | 2]
a) None  
b) One  
c) Infinite  

Q25. (Problem-solving)
Let  
A =
[1 0 2]
[0 1 3]
[1 1 5]
b = [3;4;7].
Rank(A)=?
a) 1  
b) 2  
c) 3  
d) 0  

Q26. (Problem-solving)
Let A be 4×4 and rank(A)=2. Nullity(A)=?
a) 1  
b) 2  
c) 3  
d) 4  

Q27. (Problem-solving)
Given a 3×3 matrix with nullity 2. Rank is:
a) 1  
b) 2  
c) 3  
d) 0  

Q28. (Problem-solving)
Which of the following RREF matrices represent **infinite solutions** to Ax=b?
a)
[1 0 1 | 2]
[0 1 2 | 1]
[0 0 0 | 1]  
b)
[1 0 1 | 2]
[0 1 2 | 1]
[0 0 0 | 0]  
c)
[1 0 | 4]
[0 1 | 5]  
d)
[0 1 | 3]

Q29. (Conceptual)
If rank(A)=1 for 4×3 matrix, then nullity is:
a) 0  
b) 1  
c) 2  
d) 3  

Q30. (Problem-solving)
Let
A =
[1 2 3]
[0 1 1]
[0 0 0], b=[4;2;k].
For consistency:
a) k = 0  
b) k = 1  
c) k = anything  
d) k = 4  

             
------------------------------------------------------------
Answer Key
------------------------------------------------------------


Q1   b  
Q2   b  
Q3   b  
Q4   a  
Q5   b  
Q6   a  
Q7   a  
Q8   b  

Q9   b  
Q10  b  
Q11  a  
Q12  b  
Q13  b  
Q14  b  
Q15  b  
Q16  a  
Q17  c  
Q18  b  
Q19  a  
Q20  b  
Q21  b  
Q22  a  
Q23  b  

Q24  c  
Q25  b  
Q26  b  
Q27  a  
Q28  b, d   (both represent infinite solutions)  
Q29  c  
Q30  a  
