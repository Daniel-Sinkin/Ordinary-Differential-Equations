# Problem
Which of the following functions specify a diffeomorphism $f: \mathbb{R} \rightarrow \mathbb{R}$ of the line onto the line:
$$
f_1(x) = 2x, f_2(x) = x^2, f_3(x) = x^3, f_4(x) = e^x, f_5(x) = e^x + x?
$$

# Solution
* $f_1^{-1}(y) = \frac{1}{2} y$ so it's a diffeomorphism.
* $f_2(x) \geq 0$ in particular $f_2(x) \neq -1$ and is therefore not surjective.
* $f_3^{-1}(y) = \sqrt[3]{y}$, so it's a diffeomorphism.
* $f_4(x) > 0$ so in particular $f_4(x) \neq -1$ and is therefore not surjective.
* $f_5'(x) = e^x + 1 > 1$ as such the function is strictly monotone increasing, $\lim_{x \rightarrow -\infty} f_5(x) = -\infty$ and $\lim_{x \rightarrow \infty} f_5(x) = +\infty$ as such the function is bijective. Because $f_5'(x) > 1$ the inverse is also differentiable, as such the function is a diffeomorphism (its inverse is $-W(1)$ where $W$ denotes the Lambert $W$ function).
