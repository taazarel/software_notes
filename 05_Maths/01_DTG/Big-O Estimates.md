# Big-O Estimates

Here we find estimates for important [[Function]]s using [[Big-O]].

## Polynomials

The leading term of a polynomial dominates its growth by determining that a polynomial of degree n, is n or less.
- $ Given a polynomial $f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$ where $a_{0},a_{1},\dots,a_{n-1},a_{n} \in \mathbb{R}$, then $f(x) \text{ is } O(x^{n})$.[^1]

### [[Logarithm]]s, Powers and [[Exponent]]ials

Theorem 1 shows that if $f(n)$ is a polynomial of degree d or less then $f(n) \text{ is } O(n^{d})$. Using theorem 1 together with the relationship $d>c>1$ then $n^{c}\text{ is }O(n^{d})$, putting these together we can see that if $d>c>1$ then:
$$
(\log_{b}n)^{c}\text{ is }O(n^{d}),\text{ but }n^{d}\text{ is not }(O(\log_{b}n)^{c})
$$
$$
n^{c}\text{ is }O(n^{d}),\text{ but }n^{d}\text{ is not } O(n^{c})
$$
We know that $\log_{b}(n) \text{ is }O(n)$ whenever $b>1$. But more generally whenever $b>1$ and $0<c,d$ we have:
$$
n^{d}\text{ is }O(b^{n}),\text{ but }b^{n}\text{ is not } O(n^{d})
$$
Ergo, every power of n is big-O of every exponential function of n with a base greater than 1. 
When $c>b>1$ we have 
$$
b^{n}\text{ is }O(c^{n}),\text{ but }c^{n}\text{ is not } O(b^{n})
$$
Lastly, if $c>1$ we get
$$
c^{n}\text{ is }O(n!),\text{ but }n!\text{ is not } O(c^{n})
$$

- & These estimates can be used to order the growth of different functions.

[^1]: This is theorem 1 in 3.2 in the DTG book.