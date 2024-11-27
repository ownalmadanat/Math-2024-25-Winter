# Math Class Work  
**Homework Date:** 20/11/2024  

### Problem  
Solve the system of equations:  
\[
\begin{aligned}
x + 2y + 3z &= 5 \\
2y + 3z &= u \\
3z &= 3
\end{aligned}
\]

### Step 1: Write in Matrix Form  
Let  
\[
A = \begin{bmatrix} 1 & 2 & 3 \\ 0 & 2 & 3 \\ 0 & 0 & 3 \end{bmatrix}, \quad
X = \begin{bmatrix} x \\ y \\ z \end{bmatrix}, \quad
B = \begin{bmatrix} 5 \\ u \\ 3 \end{bmatrix}.
\]  
The system can be written as:  
\[
AX = B
\]

### Step 2: Calculate the Determinant of \( A \)  
\[
\text{Det}(A) = 1 \cdot (2 \cdot 3 - 3 \cdot 0) - 2 \cdot (0 \cdot 3 - 3 \cdot 0) + 3 \cdot (0 \cdot 3 - 2 \cdot 0) = 6
\]

### Step 3: Find \( A^{-1} \)  
\[
A^{-1} = \frac{1}{\text{Det}(A)} \cdot \text{Adj}(A)
\]  
The result is:  
\[
A^{-1} = \frac{1}{6} \begin{bmatrix} 1 & -1 & 0 \\ 0 & 3/2 & -1/2 \\ 0 & 0 & 1/3 \end{bmatrix}
\]

### Step 4: Solve for \( X \)  
\[
X = A^{-1} \cdot B
\]  
Substituting values:  
\[
X = \frac{1}{6} \begin{bmatrix} 1 & -1 & 0 \\ 0 & 3/2 & -1/2 \\ 0 & 0 & 1/3 \end{bmatrix} \cdot \begin{bmatrix} 5 \\ u \\ 3 \end{bmatrix}
\]

### Step 5: Compute  
\[
x = 5 + (-4) + 0 = 1  
\]  
\[
y = 0 + 2 + \left(-\frac{3}{2}\right) = \frac{1}{2}  
\]  
\[
z = 0 + 0 + 1 = 1  
\]

### Final Answer  
\[
x = 1, \quad y = \frac{1}{2}, \quad z = 1
\]
# Solutions to Systems of Equations Using the Inverse Matrix Method

## Problem 1

### System of Equations
\[
\begin{aligned}
x + 2y + 3z &= 5, \\
2y + 3z &= 4, \\
3z &= 3.
\end{aligned}
\]

### Step 1: Matrix Form
The system can be written in matrix form as:
\[
A \cdot \mathbf{x} = \mathbf{b},
\]
where:
\[
A = 
\begin{bmatrix}
1 & 2 & 3 \\
0 & 2 & 3 \\
0 & 0 & 3
\end{bmatrix}, \quad 
\mathbf{x} = 
\begin{bmatrix}
x \\
y \\
z
\end{bmatrix}, \quad
\mathbf{b} = 
\begin{bmatrix}
5 \\
4 \\
3
\end{bmatrix}.
\]

### Step 2: Inverse of \( A \)
The inverse of \( A \) is:
\[
A^{-1} = 
\begin{bmatrix}
1 & -1 & 0 \\
0 & 1/2 & -1/2 \\
0 & 0 & 1/3
\end{bmatrix}.
\]

### Step 3: Solve for \( \mathbf{x} \)
Using \( \mathbf{x} = A^{-1} \cdot \mathbf{b} \):
\[
\mathbf{x} = 
\begin{bmatrix}
1 & -1 & 0 \\
0 & 1/2 & -1/2 \\
0 & 0 & 1/3
\end{bmatrix}
\begin{bmatrix}
5 \\
4 \\
3
\end{bmatrix}
=
\begin{bmatrix}
1 \\
1/2 \\
1
\end{bmatrix}.
\]

### Final Solution
\[
x = 1, \quad y = \frac{1}{2}, \quad z = 1.
\]

---

## Problem 2

### System of Equations
\[
\begin{aligned}
x_1 + 2x_2 + 3x_3 &= 41, \\
4x_1 + 5x_2 + 6x_3 &= 93, \\
7x_1 + 8x_2 + 9x_3 &= 145.
\end{aligned}
\]

### Step 1: Matrix Form
The system can be written in matrix form as:
\[
A \cdot \mathbf{x} = \mathbf{b},
\]
where:
\[
A = 
\begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
7 & 8 & 9
\end{bmatrix}, \quad 
\mathbf{x} = 
\begin{bmatrix}
x_1 \\
x_2 \\
x_3
\end{bmatrix}, \quad
\mathbf{b} = 
\begin{bmatrix}
41 \\
93 \\
145
\end{bmatrix}.
\]

### Step 2: Determinant of \( A \)
The determinant of \( A \) is:
\[
\text{det}(A) = 0.
\]

Since the determinant is zero, the matrix \( A \) is not invertible, and the system does not have a unique solution.
