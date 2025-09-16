# Closure

Given a [[Relation]] $R$ on a [[Set]] $A$, then the [[Closure]] of $R$ for a property $\mathbf{P}$, if it exists, is the relation $S$ on $A$ with property $\mathbf{P}$ and is a [[Subset]] of every [[Subset]][^1] of the [[Cartesian Product]] of A containing $R$ with property $\mathbf{P}$.

## Intuition


## Properties of Closures
### Reflexive Closure

The reflexive closure of $R$ on $A$ is found by adding all $(a,a)\in R$ for all $a \in A$.
We can let $\Delta = \{ (a,a):a\in A \}$ be the diagonal [[Relation]]. Then we find the reflexive closure simply by doing a [[Union of Sets]] ($R\cup \Delta$).

### Symmetric Closure

The symmetric closure of $R$ on $A$ is found by adding $(b,a)$ to $R$ for all $(a,b) \in R$.
We define the relation $R^{-1}=\{ (b,a):(a,b)\in R \}$. Then the symmetric closure is found by doing a [[Union of Sets]] ($R\cup R^{-1}$).

### Transitive Closure

Finding the transitive closure of $R$ on $A$ is a bit harder. 
A relation is transitive if:
$$
(a,b)\in R\land(b,c)\in R \to(a,c)\in R
$$
The transitive closure of a relation $R$ is defined as $R^{*}$.

We can solve this graphically by adding a path from a to b, whenever there is a path (of any length) from b to c.
![[Pasted image 20250916135252.png]]

For matrices, we can find the transitive closure, as it is defined:
$$
R^{*}=\bigcup_{i=1}^{\infty}R^{n}
$$
[^1]: Just means that it must be the **smallest** subset that exists with the property.