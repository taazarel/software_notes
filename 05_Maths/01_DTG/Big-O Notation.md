# Big-O Notation

Is used to estimate the growth of a [[Function]] used in an [[Algorithm]] while ignoring hardware and software differences between systems.
Sometimes called a **Landau** symbol, after the German mathematician Edmund Landau.

- $ Given two [[Function]]s; $f,g:=\mathbb{Z}\text{ or }\mathbb{R}\to \mathbb{R}$. We say that $f(x)$ is $O(g(x))$ if there are constants C and k such that $\lvert f(x) \rvert \leq C\lvert g(x) \rvert$ whenever $x>k$.[^1]

This means that f grows slower than g multiplied by a constant.
The constants C and k are called **Witnesses** to the relationship of $f(x)\text{ is }O(g(x))$.

## Method for using Big-O

We can find a pair of witnesses by selecting a value of k where the size of $\lvert f(x) \rvert$ can be easily estimated. Then checking whether this will give us a valid C.


[^1]: This is read as "$f(x)$ is big-oh of $g(x)$"
