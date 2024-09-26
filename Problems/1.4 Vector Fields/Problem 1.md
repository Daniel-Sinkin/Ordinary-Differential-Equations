# Definitions
## Phase Velocity
By the phase velocity $v(x)$ of the flow $g^t$ at a point $x \in M$ is meant the vector representing the velocity of motion of the phase point, i.e.,
$$
\left.\frac{d}{dt}\right|_{t = 0} g^tx = v(x).\quad(3)
$$

The left hand side of $(3)$ is often denoted by $\dot{x}$. Note that the derivative is defined, since the motion is a differentiable mapping of a domain in Euclidean spac.

# Problem
Prove that
$$
\left.\frac{d}{dt}\right|_{t = \tau} g^tx = v(g^\tau x),
$$
i.e., that at every instant of the vector representing the velocity of motion of the phase point equals the vector representing the phase velocity at the very point of phase space occupied by the moving point at the given time.

# Solution
$$
\begin{aligned}
v(g^\tau x) &= \left.\frac{d}{dt}\right|_{t = 0} g^t(g^\tau x) \\
&= \left.\frac{d}{dt}\right|_{t = 0}g^{t + \tau} x \\
&= \lim_{\varepsilon \rightarrow 0} \frac{g^{\varepsilon + \tau}x - g^\tau x}{\varepsilon} \\
&= \lim_{\varepsilon' \rightarrow \tau} \frac{g^{\varepsilon'}x - g^{\tau} x}{\varepsilon' - \tau} \\
&= \left.\frac{d}{dt}\right|_{t = \tau} g^tx.
\end{aligned}
$$