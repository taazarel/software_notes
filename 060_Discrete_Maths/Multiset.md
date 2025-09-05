# Multisets

A multiset is an unordered collection of elements where  one element can be a member more than once.

In multisets, we can operate as we do with normal [[Set]]s, except we have to list each element the number of times it occurs.

We can use [[Multiplicity]] to denote that we are using a [[Multiset]]. 

- $ This looks like so:
$$
S = \{ m_{1}\cdot a_{1},m_{2}\cdot a_{2},\dots,m_{n}\cdot a_{n} \}
$$

The numbers $m_{i}$ are called the multiplicities of the elements $a_{i}$. Elements not included in a multiset, are assigned the value of zero for their multiplicity.

## Cardinality

The [[Cardinality]] of a [[Multiset]] is defined as the sum of the multiplicities of the sets elements.

$$
\lvert S \rvert = \sum_{i=1}^{n} m_{i}
$$

## Union of Multisets

The union of a multiset is the multiset of multisets P and Q, in which the multiplicity of an element is the maximum of its multiplicities in P and Q.

- $ Denoted $P\cup Q$

## Intersection of Multisets

The intersection of a multiset is the multiset of multisets P and Q, in which the multiplicity of an element is the minimum of its multiplicities in P and Q.

- $ Denoted $P \cap Q$

## Difference of Multisets

The difference of P and Q is the multiset with the multiplicity of an element equal to the multiplicity of P minus Q, to a minimum of 0.

- $ Denoted $P-Q$

## Sum of Multisets

The sum of P and Q is the multiset with the multiplicity of an element equal to the multiplicity of P plus Q.

- $ Denoted $P+Q$