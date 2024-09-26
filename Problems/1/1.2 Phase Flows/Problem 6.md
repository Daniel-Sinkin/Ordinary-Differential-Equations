# Problem 6
Prove that the shift
$$
\begin{aligned}
h^s : \mathbb{R} \times M &\rightarrow \mathbb{R} \times M \\
(t, x) &\mapsto (t + s, x)
\end{aligned}
$$
of extended phase space along the time axis carries integral curves into integral curves.

# Solution
Note that $h^s(t, \varphi^t(x)) = (t + s, \varphi^t(x))$, and we can write
$$
y := \varphi^{-s}x,
$$
i.e., the point we obtain by flowing time back by $s$ units starting from $x$, that can be written as $\varphi^sy = x$ and as such
$$
h^s(t, \varphi^t(x)) = (t + s, \varphi^t(x)) = (t + s, \varphi^t(\varphi^s(x))) = (t + s, \varphi^{t + s}(y))
$$
is another integral curve.