# Problem 4
Prove that there is one and only one integral curve passing through every point of extended phase space.

# Solution
The notation in the book is a bit convolution, an integral curve is simply the map
$$
\begin{aligned}
\gamma : \mathbb{R} &\rightarrow \mathbb{R} \times M \\
t &\mapsto (t, \varphi^t(x))
\end{aligned}
$$

A "point" in the extended phase space is simply a pair $(t, \varphi^t(x))$. The proof is similar to Problem 3, every pair $(t, \varphi^t(x))$ is part of its own integral curve, which proves existance.

Suppose there are two integral curves $\gamma, \eta$ such that $\gamma(t) = \eta(s)$ then $t = s$ and
$$
(t, \varphi^t(x)) = (t, \varphi^s(y))
$$
by uniqueness in Problem 3 this already means those are the same motion.

Uniqueness in particular implies that integral curves can't have self-intersections.