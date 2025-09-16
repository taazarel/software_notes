# Relation

This is the most direct way of expressing a relationship between two [[Set]]s.
Given sets A and B, a binary relation R from A to B is a subset of the [[Cartesian Product]] $A\times B$.[^1]
Therefore a [[Relation]] is a [[Set]] of ordered tuples.

## Properties of Relations

### Reflexive

A relation R on set A is called reflexive if $(a,a)\in R$ for every element in the set A; $a \in A$.
![[Pasted image 20250916124532.png]]

### Symmetry and Anti-symmetry

A relation is called symmetric if $(b,a)\in R$ whenever $(a,b)\in R$ for all $a,b \in A$.
![[Pasted image 20250916124622.png]]

A relation is anti-symmetric if for all $a,b\in A$ there exists symmetry $(a,b)\in R$ and $(b,a)\in R$ whilst $a=b$.
![[Pasted image 20250916124654.png]]

### Transitivity

A relation R on a set A is transitive if whenever $(a,b)\in R$ and $(b,c)\in R$ then $(a,c)\in R$ exists for all $a,b,c\in A$.

## Representations of Relations
### Matrix 
Given two sets, we can use them as the axis for a table, then do a [[Boolean]] on each intersection. This will make the relation clear.
![[Pasted image 20250916124036.png]]
### Graphical
Only works on relations which are [[Subset]]s on a [[Cartesian Product]] of a single single [[Set]] $(A \times A)$.
![[Pasted image 20250916124313.png]]

[^1]: A Relation on set A, is a relation from A to A.