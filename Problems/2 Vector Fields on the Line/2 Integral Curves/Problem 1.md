$$
\dot{x} = v(x)\quad(1)
$$

# Problem
Let $x = \arctan(t)$ be a solution of equation (1). Prove that $x = \arctan(t + 1)$ is also a solution.

# Solution
Let $x(t) = \arctan(t), y(t) = \arctan(t + 1)$ then
$$
\dot{y}(t) = \frac{1}{1 + (1 + t)^2}
$$
and
$$
\dot{x}(t) = \frac{1}{1 + t^2}
$$
therefore $\dot{y}(t) = \dot{x}(t + 1)$. With that we can compute
$$
\dot{y}(t) = \dot{x}(t + 1) = v(x(t + 1)) = v(y(t)).
$$
