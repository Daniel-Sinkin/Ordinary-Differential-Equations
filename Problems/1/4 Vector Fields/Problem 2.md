# Definitions
## Components of the velocity vector
If $x_1, \dots, x_n$ are the coordinates in our Euclidean space, so that $x_i: M \to \mathbb{R}$, then the velocity vector $\mathbf{v}(x)$ is specified by $n$ functions $v_i: M \to \mathbb{R}, i = 1, \dots, n$, called the *components* of the velocity vector:
$$
v_i(x) = \frac{d}{dt} \bigg|_{t=0} x_i(g^t x).
$$
# Problem
Prove that $v_i$ is a function of class $C^{r-1}$ if the one-parameter group $g: \mathbb{R} \times M \to M$ is of class $C^r$.

# Solution
The way to think about it is, note that if $M \subseteq \mathbb{R}^n$ then we can write
$$
\varphi^t(x) = (p_1(x), p_2(x), \dots, p_n(x))
$$
and then
$$
x_i(\varphi^t(x)) = p_i(x)
$$
and $v_i(x) = p_i'(x)$. If we write $g(t, x) = g^t(x)$ then $g$ is a $C^r$ function and
$$
\frac{d}{dt} \bigg|_{t = t_0} g(t, x) = (p_1'(t_0), p_2'(t_0), \dots, p_n'(t_0))
$$
To avoid confusion we write $\pi_j := x_j$ and recall that $\frac{d\pi_j}{dx_i} = \delta_{ij}$. 
The projection is a function
$$
\pi_i : \mathbb{R}^n \rightarrow \mathbb{R}
$$
whose derivative can be written as
$$
D\pi_i : \mathbb{R}^n \rightarrow \mathbb{R}^n
$$
and for fixed $x$ the function $g(\cdot, x) : \mathbb{R} \rightarrow \mathbb{R}^n$, whose derivative is given as a map
$$
D(g(\cdot, x)): \mathbb{R} \rightarrow \mathbb{R}^n.
$$
By chain rule we then obtain
$$
v_i = \frac{d}{dt}\bigg|_{t = 0} \pi_ig^t(x) = D\pi_i(\underbrace{g^0(x)}_{=x}) D(g(\cdot, x))(t) = D\pi_i(x)D(g(\cdot, x))(t)
$$

$\pi_i$ is a smooth function and $g(t, x) \in C^r$ as such $v_i$ is $C^{r - 1}$.

As a sidenote $D\pi_i(x) = (0, 0, \dots, 1, 0, \dots 0)$ where the $1$ is in the ith position, as such the entire derivative is equal to
$$
\pi_i\left(\frac{d}{dt}\bigg|_{t = 0} g(t, x)\right),
$$
this can be written more generally as
$$
D(\pi(f)) = \pi(D(f))
$$
i.e. the coordinate projections commute the differentiation in this sense.