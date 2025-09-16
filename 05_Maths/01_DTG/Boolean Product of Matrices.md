# Boolean Product of Matrices

Given a matrix $M_{r,s}$ and matrix $N_{s,t}$. Their product $P = M_{r,s}N_{s,t}$ can be found by finding each element $p_{ij}$ given by: 
$$
p_{ij}:=\sum_{k=1}^{s} m_{ik}n_{kj} = m_{i 1}n_{1 j} + m_{i 2}n_{2 j} + \dots m_{is}n_{sj}
$$

The **Boolean** product (denoted $\odot$), just replaces products with [[Conjunction]]s and sums with [[Disjunction]]s. So for $Q = M_{r,s}\odot N_{s,t}$ the entry $q_{ij}$ is given by:
$$
q_{ij}:= \bigvee_{k=1}^{s} (m_{ik}\land n_{kj})=(m_{i 1} \land n_{1j})\lor(m_{i 2}\land n_{2j}) \lor \dots \lor (m_{is}\land n_{sj})
$$
[[Composite of Sets]] can be represented as matrices, by using the [[Boolean Product of Matrices]]. 
