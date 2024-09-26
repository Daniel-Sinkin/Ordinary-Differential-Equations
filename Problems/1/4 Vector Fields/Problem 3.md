# Definition
## Vector field
Let $M$ be a domain in Euclidean space with coordinates
$$
x_1, \dots, x_n: M \rightarrow \mathbb{R},
$$
and suppose that with every point $x \in M$ there is associated the vector $v(x)$ emanating from $x$. Then this defines a vector field $v$ on $M$, specified in the $x_i$ coordinate sysmte by $n$ differentiable functions
$$
v_i: M \rightarrow \mathbb{R}
$$

# Problem
Prove that if $x$ is a fixed point of a phase flow, then $v(x) = 0$.

# Solution
Suppose $v(x) \neq 0$ then there exists $i$ such that $v_i(x) \neq 0$, i.e. there exists $i$ such that
$$
\frac{d}{dt} \bigg|_{t = 0} x_i(g^t(x)) \neq 0
$$
which in turn means that $t \mapsto x_i(g^t(x))$ can't be locally constant around $0$, i.e. for all $\varepsilon > 0$ there exists $t_\varepsilon \in (-\varepsilon, \varepsilon) \backslash \{0\}$ such that
$$
x_i(g^{t_\varepsilon}(x)) \neq x_i(g^0(x)) = x,
$$
as such $x$ can't be a fixed point if the velocity vector does not vanish.