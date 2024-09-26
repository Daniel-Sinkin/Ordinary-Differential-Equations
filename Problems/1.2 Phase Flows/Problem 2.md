## Definition: One-parameter group of transformations
A family $(g^t)$ of mappings of a set $M$ into itself, labelled by the set of all real numbers $(t \in \mathbb{R})$, is called a one-parameter group of transformations of $M$ if
$$
g^{t + s} = g^tg^s
$$
for all $s, t \in \mathbb{R}$ and $g^0$ is the identity mapping (which leaves every point fixed).

# Problem 2
Prove that a one-parameter group of transformations is a commutative group and that every mapping
$$
g^t : M \rightarrow M
$$
is one-to-one.

## Proof
Denote that group by $G = (\{g^t\}_t, \cdot)$ where
$$
g^t g^s = g^{t + s}
$$
is the group operation. $\operatorname{id} := g^0$ is the identity element of $G$, of $t \in \mathbb{R}$ we have $-t \in \mathbb{R}$ and
$$
g^tg^{-t} = g^{t - t} = g^0 = \operatorname{id}.
$$
Let $t, s, r \in \mathbb{R}$ then
$$
(g^t g^s) g^r = g^{t + s} g^r = g^{(t + s) + r} = g^{t + (s + r)} = g^t g^{s + r} = g^t (g^s g^r)
$$
where we have used the associativity of addition in (the field) $\mathbb{R}$.
$$
g^tg^s = g^{t + s} = g^{s + t} = g^s g^t.
$$
As such $G$ is an Abelian group.  A more abstract approach to proving this is to note that $(\mathbb{R}, +)$ is a commutative group we have a group isomorphism between our groups defined by
$$
t \mapsto g^t.
$$
It remains to show that $g^t : M \rightarrow M$ is one-to-one. Suppose $g^t$ is not injective, i.e. there exist $p, q \in M, p \ne q$ such that
$$
g^t(p) = g^t(q),
$$
but that would imply that
$$
g^{-t}(g^t(p)) = g^{-t}(g^t(q))
$$
which means that
$$
p = q,
$$
a contradiction. As such $g^t$ is injective (i.e. one-to-one).