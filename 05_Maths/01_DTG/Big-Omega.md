# Big-$\Omega$ Notation

Big-$\Omega$ is the opposite of [[Big-O]] notation. It literally just goes the other direction.

- $ Given two [[Function]]s; $f,g:=\mathbb{Z}\text{ or }\mathbb{R}\to \mathbb{R}$. We say that $f(x)$ is $\Omega(g(x))$ if there are constants C and k such that $\lvert f(x) \rvert \geq C\lvert g(x) \rvert$ whenever $x>k$.

A very strong connection between these is that $f(x)$ is $\Omega(g(x))$ if and only if $g(x)$ is $O(f(x))$. Ergo, they are [[Inverse Function]]s.