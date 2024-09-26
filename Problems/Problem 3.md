## Definitions: Phase
## Phase Flow, phase space, phase points
A pair $(M, \{ g^t \})$ consisting of a set $M$ and a one-parameter group $\{g^t\}$ of transformations of $M$ into itself is called a *phase flow*. The set $M$ is called the *phase space* of the flow, and its elements are called *phase points*.

## Motion
Let$x \in M$ be any phase point, and consider the mapping
$$
\varphi : \mathbb{R} \to M, \quad \varphi(t) = g^t x,\quad(2)
$$
of the real line into phase space. Then the mapping (2) is called the *motion* of the point $x$ under the action of the flow $(M,\{g^t\})$.

## Phase Curve
the mapping $(2)$ is called a *phase curve* of the flow $(M,\{g^t\})$. Thus, a phase curve is a subset of phase space.

# Problem 3
Prove that there is one and only one phase curve passing through every point of phase space.

# Solution
For existence just note that $g^0(p)$ is part of a phase curve for every $p$, so every phase space point is part of its own phase curve.

For uniqueness, it suffices to show that if two phase curves touch at one point then they are equal. Let $x, y \in M$ such that $g^{t_0}x = g^{t_1}y$ that is equivalent to
$$
g^0 x = g^{t_1-t_0} y,
$$
note that $g^0x = x$ and let $s := t_1 - t_0$.

Now consider an arbitrary point $x' = g^ax$ then
$$
x' = g^ax = g^a(g^sy) = g^{a + s}y,
$$
as such, because $x'$ was arbitrary, the phase curves of $x$ and $y$ are the same.