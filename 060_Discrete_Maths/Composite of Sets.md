# Composite of Sets

This is found in definition 6 section 9.1 of [Ros].

Given sets A, B, and C, and [[Relation]]s R on set A and B, and S on set B and C.

The composite of R and S is the relation of ordered pairs $(a,c)$ where $a \in A,c\in C$, and where there exists an element b such that $(a,b)\in R,(b,c)\in S$. This is denoted as $R \circ S$.

$$
R \circ S = \{ (a,c) | (a \in A\land c\in C)\land (\exists(a,b)\in R \land \exists(b,c)\in S) \}
$$