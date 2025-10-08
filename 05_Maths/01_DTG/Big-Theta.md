# Big-$\Theta$ Notation

This is used to find the upper and lower bounds of a [[Function]] in, so we can find its order of growth.

- $ Given two [[Function]]s $f,g:= \mathbb{Z}\text{ or }\mathbb{R} \to \mathbb{R}$. We say that $f(x)$ is $\Theta(g(x))$ if $f(x)$ is both $O(g(x))$ and $\Omega(g(x))$. 
- & When $f(x) = \Theta(g(x))$ we say that $f$ is big theta of $g(x)$, that $f(x)$ is of order $g(x)$ and that $f(x)$ and $g(x)$ is of same order.[^1]

## Theorem Four

Let $f(x)=a_{n}x^{n}+a_{n-1}x^{n-1}+\dots+a_{1}x+a_{0}$, where $a_{0},a_{1},\dots, a_{n} \in \mathbb{R}$ with $a_{0}\neq 0$, then $f(x)$ is of order $x^{n}$.

[^1]: When f is big theta of g, then g is also big theta of f.