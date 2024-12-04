# Equations of Planes in Space - Solutions

---

## 1. The plane passes through points \(A(1, 2, 3)\), \(B(3, 4, 5)\), and \(C(2, 1, 4)\)

### Solution:
The equation of a plane can be written as:
$$a(x - x_1) + b(y - y_1) + c(z - z_1) = 0,$$
where \((a, b, c)\) is the normal vector. To find the normal vector, compute:
$$\vec{AB} = (3 - 1, 4 - 2, 5 - 3) = (2, 2, 2),$$
$$\vec{AC} = (2 - 1, 1 - 2, 4 - 3) = (1, -1, 1).$$

The normal vector is:

$$\vec{n} = \vec{AB} \times \vec{AC}.$$

Compute the cross product:

$$\vec{n} = 
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 2 & 2 \\
1 & -1 & 1
\end{vmatrix}
= \mathbf{i}(2 - (-2)) - \mathbf{j}(2 - 2) + \mathbf{k}(-2 - 2),$$
$$\vec{n} = (4, 0, -4).$$

Now use the point \(A(1, 2, 3)\) to find the equation:
$$4(x - 1) + 0(y - 2) - 4(z - 3) = 0.$$
Simplify:
$$x - 4y + 3z = 8.$$

### Answer:
$$x - 4y + 3z = 8$$

---

## 2. The plane passes through point \(A(1, 2, 3)\) and is parallel to the plane \(2x + 3y + 4z = 5\)

### Solution:
The plane parallel to \(2x + 3y + 4z = 5\) has the same normal vector \((2, 3, 4)\). Using the point \(A(1, 2, 3)\), the equation is:
$$
2(x - 1) + 3(y - 2) + 4(z - 3) = 0.
$$
Simplify:
$$
2x + 3y + 4z = 20.
$$

### Answer:
$$
2x + 3y + 4z = 20
$$

---

## 3. The plane passes through point \(A(1, 2, 3)\) and is perpendicular to the normal vector \(\vec{n} = [2, 3, 4]\)

### Solution:
# Finding the Equation of the Plane

We are tasked with finding the equation of a plane that:
1. Passes through the point \( A(1, 2, 3) \),
2. Is perpendicular to the normal vector \( \mathbf{n} = [2, 3, 4] \).

## General Equation of a Plane

The general equation of a plane is:
$$n_1(x - x_0) + n_2(y - y_0) + n_3(z - z_0) = 0$$
where:
- \( (x_0, y_0, z_0) \) is a point on the plane,
- \( [n_1, n_2, n_3] \) is the normal vector to the plane.

## Substituting Given Values

From the problem:
- The point \( A(1, 2, 3) \) gives \( (x_0, y_0, z_0) = (1, 2, 3) \),
- The normal vector \( \mathbf{n} = [2, 3, 4] \) gives \( n_1 = 2 \), \( n_2 = 3 \), \( n_3 = 4 \).

Substitute these values into the general equation:
$$2(x - 1) + 3(y - 2) + 4(z - 3) = 0$$

## Expanding the Equation

Expand the terms:
$$2x - 2 + 3y - 6 + 4z - 12 = 0$$

Combine like terms:
$$2x + 3y + 4z - 20 = 0$$

## Final Equation of the Plane

Thus, the equation of the plane is:
$$2x + 3y + 4z = 20$$

---

## 4. Find the line of intersection of the planes \(2x + 3y + 4z = 5\) and \(3x + 4y + 2z = 6\)

### Solution:
We solve the system of equations:
1. \(2x + 3y + 4z = 5\),
2. \(3x + 4y + 2z = 6\).

Let \(z = t\). From the first equation:
$$
2x + 3y = 5 - 4t.
$$

From the second equation:
$$
3x + 4y = 6 - 2t.
$$

Eliminate \(y\) by multiplying the first equation by 4 and the second equation by 3:
$$
8x + 12y = 20 - 16t,
$$
$$
9x + 12y = 18 - 6t.
$$

Subtract:
$$
x = -2 + 10t.
$$

Substitute \(x = -2 + 10t\) into \(2x + 3y = 5 - 4t\):
$$
2(-2 + 10t) + 3y = 5 - 4t,
$$
$$
-4 + 20t + 3y = 5 - 4t,
$$
$$
3y = 9 - 24t, \quad y = 3 - 8t.
$$

Thus, the parametric equation of the line is:
$$
(x, y, z) = (-2, 3, 0) + t(10, -8, 1).
$$

### Answer:
$$
(x, y, z) = (-2, 3, 0) + t(10, -8, 1)
$$

---

## 5. Write the equation of the plane passing through \(A(1, 2, 3)\) and parallel to vectors \(\vec{v_1} = [1, 0, 1]\) and \(\vec{v_2} = [0, 1, -1]\)

### Solution:
The normal vector is:
$$
\vec{n} = \vec{v_1} \times \vec{v_2}.
$$
Compute the cross product:
$$
\vec{n} = 
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
1 & 0 & 1 \\
0 & 1 & -1
\end{vmatrix}
= \mathbf{i}(0 - (-1)) - \mathbf{j}(1 - 0) + \mathbf{k}(1 - 0),
$$
$$
\vec{n} = (1, -1, 1).
$$

Using point \(A(1, 2, 3)\), the equation is:
$$
1(x - 1) - 1(y - 2) + 1(z - 3) = 0.
$$
Simplify:
$$
x - y + z - 2 = 0.
$$

### Answer:
$$
x - y + z - 2 = 0
$$

---

## 6. Find a plane parallel and perpendicular to \(2x + 3y + 4z = 5\)

### Parallel Plane:
The equation of a parallel plane is:
$$
2x + 3y + 4z = 1.
$$

### Perpendicular Plane:
Choose a new normal vector \((1, -2, 1)\). The equation of the perpendicular plane is:
$$
x - 2y + z = 0.
$$

### Answer:
**Parallel Plane:** 
$$
2x + 3y + 4z = 1
$$
**Perpendicular Plane:** 
$$
x - 2y + z = 0
$$

---

## 7. Find the distance from \(A(1, 2, 3)\) to the plane \(2x + 3y + 4z = 5\)

### Solution:
The distance formula is:
$$
d = \frac{|a x_1 + b y_1 + c z_1 + d|}{\sqrt{a^2 + b^2 + c^2}},
$$
where \((x_1, y_1, z_1) = (1, 2, 3)\), and the plane is \(2x + 3y + 4z - 5 = 0\).

Substitute:
$$
d = \frac{|2(1) + 3(2) + 4(3) - 5|}{\sqrt{2^2 + 3^2 + 4^2}},
$$
$$
d = \frac{|2 + 6 + 12 - 5|}{\sqrt{4 + 9 + 16}} = \frac{15}{\sqrt{29}} \approx 2.78.
$$

### Answer:
$$
d = \frac{15}{\sqrt{29}} \quad \text{or approximately } 2.78
$$

---

## 8. The plane intersects the coordinate axes at points \(A(2, 0, 0)\), \(B(0, 3, 0)\), and \(C(0, 0, 4)\)

### Solution:
The general equation is:
$$
\frac{x}{2} + \frac{y}{3} + \frac{z}{4} = 1.
$$
Simplify:
$$
6x + 4y + 3z = 12.
$$

### Answer:
$$
6x + 4y + 3z = 12
$$

---

## 9. Calculate the angle between the plane \(x + y + z = 1\) and the plane \(x = 0\)

### Solution:
The angle \(\theta\) is given by:
$$
\cos \theta = \frac{|\vec{n_1} \cdot \vec{n_2}|}{\|\vec{n_1}\| \|\vec{n_2}\|}.
$$
Here, \(\vec{n_1} = (1, 1, 1)\) and \(\vec{n_2} = (1, 0, 0)\).

Compute:
$$
\vec{n_1} \cdot \vec{n_2} = 1(1) + 1(0) + 1(0) = 1,
$$
$$
\|\vec{n_1}\| = \sqrt{1^2 + 1^2 + 1^2} = \sqrt{3}, \quad \|\vec{n_2}\| = \sqrt{1^2} = 1.
$$
$$
\cos \theta = \frac{1}{\sqrt{3}}, \quad \theta = \cos^{-1}\left(\frac{1}{\sqrt{3}}\right) \approx 54.74^\circ.
$$

### Answer:
$$
\theta \approx 54.74^\circ
$$

---

## 10. Find the vector perpendicular to the plane \(x + y + z = 1\)

### Solution:
The normal vector to the plane is:
$$
(1, 1, 1).
$$

### Answer:
$$
(1, 1, 1)
$$
