# Question on Cramer's Rule

Given:
$$
\begin{cases}
2x_1 - 3x_2 = 7 \\
3x_1 + 5x_2 = 2
\end{cases}
$$

1. Define the Determinant

For a system of equations:
$$
\begin{cases}
a x_1 + b x_2 = e \\
c x_1 + d x_2 = f
\end{cases}
$$

2. Solution

### Using Cramer's Rule:
$x_1 = \frac{D_{x1}}{D}$ and $x_2 = \frac{D_{x2}}{D}$

where:

$D = \begin{vmatrix} a & b \\ c & d \end{vmatrix} = ad - bc$

$D_{x1} = \begin{vmatrix} e & b \\ f & d \end{vmatrix} = ed - bf$

$D_{x2} = \begin{vmatrix} a & e \\ c & f \end{vmatrix} = af - ec$

### Substituting values:

$D = 2 \cdot 5 + 3 \cdot 3 = 10 + 9 = 19$

$D_{x1} = 7 \cdot 5 + 3 \cdot 2 = 35 + 6 = 41$

$D_{x2} = 2 \cdot 7 - 3 \cdot 2 = 14 - 21 = -17$

So,

$x_1 = \frac{D_{x1}}{D}$ and $x_2 = \frac{D_{x2}}{D}$
