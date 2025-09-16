# Composite of Sets/Relations

This is found in definition 6 section 9.1 of [Ros].

Given sets A, B, and C, and [[Relation]]s R on set A and B, and S on set B and C.

The composite of R and S is the relation of ordered pairs $(a,c)$ where $a \in A,c\in C$, and where there exists an element b such that $(a,b)\in R,(b,c)\in S$. This is denoted as $S \circ R$.

$$
S \circ R = \{ (a,c) | (a \in A\land c\in C)\land (\exists(a,b)\in R \land \exists(b,c)\in S) \}
$$

The composite of relations is the same as the product of those same relations.

## Representation with matrices
![[Pasted image 20250916132930.png]]
$$
M_{R}=\begin{bmatrix}
1 & 1 \\
1 & 0
\end{bmatrix},\quad
M_{S}=\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 1
\end{bmatrix}
$$
Then we will find
$$
M_{R}\odot M_{S}=
\begin{bmatrix}
1 & 1 & 1 \\
1 & 0 & 0
\end{bmatrix}
$$
Where row one is Alice, row two is Bob, column one is artist, two is insurance and three is rockets.