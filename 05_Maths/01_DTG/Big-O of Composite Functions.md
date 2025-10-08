# Big-O of Composite Functions

## Theorem two
Given $f_{1}(x) \text{ is } O(g_{1}(x))$ and $f_{2}(x)\text{ is }O(g_{2}(x))$.
Then $(f_{1}+f_{2})(x)\text{ is }O(g(x))$ where $g(x)=max(\lvert g_{1}(x) \rvert,\lvert g_{2}(x) \rvert)$ and $x>max(k_{1},k_{2})$ for all x.

## Corollary one
If $f_{1}(x)$ and $f_{2}(x)$ both are $O(g(x))$ then: $(f_{1}+f_{2})(x)$ is $O(g(x))$.

## Theorem three
For products of [[Function]]s we have
Given $f_{1}(x)$ is $O(g_{1}(x))$ and $f_{2}(x)$ is $O(g_{2}(x))$. Then $f_{1}f_{2}(x)$ is $O(g_{1}(x)g_{2}(x))$.


