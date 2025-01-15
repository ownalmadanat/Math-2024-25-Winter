## Solution

The position of the particle is given by:
$$x(t) = 3t^2 - 6t + 1$$

### 1. Velocity \( V(t) = x'(t) \)

To find the velocity, differentiate \( x(t) \):
$$V(t) = x'(t) = \frac{d}{dt}[3t^2 - 6t + 1]$$
$$V(t) = 6t - 6$$

---

### 2. Acceleration \( a(t) = x''(t) \)

To find the acceleration, differentiate \( V(t) \):
$$a(t) = V'(t) = \frac{d}{dt}[6t - 6]$$
$$a(t) = 6$$

---

1. **Velocity** at \( t = 2 \):
$$V(2) = 6(2) - 6$$
$$V(2) = 12 - 6 = 6$$

1. **Acceleration** at \( t = 2 \):
$$a(2) = 6$$

---

### Final Results:

- Velocity at \( t = 2 \):
  $$V(2) = 6$$

- Acceleration at \( t = 2 \):
  $$a(2) = 6$$

![alt text](image-3.png)




## Problem 6:
The profit function is given by:

$$ P(u) = -2u^2 + 50u - 300 $$

where \( u \) is the number of units sold. We need to find the number of units that maximize profit.

### Solution:

1. Find the derivative of \( P(u) \):
   $$ P'(u) = -4u + 50 $$

2. Set \( P'(u) = 0 \) to find the critical points:
   $$ -4u + 50 = 0 \quad \Rightarrow \quad u = \frac{50}{4} = 12.5 $$


### Final Answer:
The number of units that maximize profit is:
$$ u = 12.5 \text{ units.} $$
![alt text](image.png)
---

## Problem 7:
You have 10 meters of string, and you need to enclose the largest possible rectangular area. Find the dimensions of the rectangle.

### Solution:

1. Let the dimensions of the rectangle be \( x \) (length) and \( y \) (width). The perimeter constraint is:
   $$2x + 2y = 10 \quad \Rightarrow \quad x + y = 5 \quad \Rightarrow \quad y = 5 - x $$

2. The area \( A \) of the rectangle is:
   $$ A = x \cdot y = x(5 - x) = 5x - x^2 $$

3. To maximize the area, find the derivative of \( A \) and set it to zero:
   $$ A'(x) = 5 - 2x  $$
  $$  A'(x) = 0 \quad \Rightarrow \quad 5 - 2x = 0 \quad \Rightarrow \quad x = \frac{5}{2} = 2.5  $$

4. Solve for \( y \):
   $$  y = 5 - x = 5 - 2.5 = 2.5  $$

### Final Answer:
The dimensions of the rectangle are:
$$ 2.5 \, \text{meters by} \, 2.5 \, \text{meters.} $$
![alt text](image-1.png)
---

## Problem 8:
Find the extremum of:
$$ f(x) = x^2 + 3x - 5 $$

### Solution:

1. Find the derivative of \( f(x) \):
   $$ f'(x) = 2x + 3 $$

2. Set \( f'(x) = 0 \) to find critical points:
   $$ 2x + 3 = 0 \quad \Rightarrow \quad x = -\frac{3}{2} $$

3. Verify the nature of the extremum using the second derivative:
   $$ f''(x) = 2  $$
   Since \( f''(x) > 0 \), the function has a **minimum** at \( x = -\frac{3}{2} \).

4. Find the minimum value by substituting \( x = -\frac{3}{2} \) into \( f(x) \):
   $$f\left(-\frac{3}{2}\right) = \left(-\frac{3}{2}\right)^2 + 3\left(-\frac{3}{2}\right) - 5$$
   $$= \frac{9}{4} - \frac{9}{2} - 5 = \frac{9}{4} - \frac{18}{4} - \frac{20}{4} = \frac{-29}{4}$$

### Final Answer:
The minimum value of \( f(x) \) is:
$$ \frac{-29}{4} \, \text{at} \, x = -\frac{3}{2}. $$
![alt text](image-2.png)
---

## Problem 9:
Find the extremum of:
$$ f(x) = \frac{x^2 + 2x + 1}{x - 1} $$

### Solution:

1. Simplify the function:
   $$  f(x) = \frac{(x + 1)^2}{x - 1}  $$

2. Find the derivative using the quotient rule:
   The quotient rule states:
   $$ \left(\frac{g(x)}{h(x)}\right)' = \frac{g'(x)h(x) - g(x)h'(x)}{[h(x)]^2}$$
   Here, \( g(x) = (x + 1)^2 \) and \( h(x) = x - 1 \). Compute \( g'(x) \) and \( h'(x) \):
   $$ g'(x) = 2(x + 1), \quad h'(x) = 1  $$
   So:
   $$ f'(x) = \frac{2(x + 1)(x - 1) - (x + 1)^2}{(x - 1)^2} $$

3. Simplify the numerator:
   $$ 2(x + 1)(x - 1) - (x + 1)^2 = 2(x^2 - 1) - (x^2 + 2x + 1) $$
   $$  = 2x^2 - 2 - x^2 - 2x - 1 = x^2 - 2x - 3  $$
   So:
   $$  f'(x) = \frac{x^2 - 2x - 3}{(x - 1)^2}  $$

4. Set \( f'(x) = 0 \):
   The numerator must be zero:
   $$ x^2 - 2x - 3 = 0 $$
   Factorize:
   $$  (x - 3)(x + 1) = 0 \quad \Rightarrow \quad x = 3 \, \text{or} \, x = -1  $$

5. Verify the nature of the critical points:
   Use a sign chart or second derivative test (details omitted for brevity).

### Final Answer:
The extremum occurs at:
$$ x = 3 \, \text{and} \, x = -1. $$

1. ∫1 dx∫1dx

The integral of a constant 11 is the constant multiplied by the variable of integration:
Solution: x+Cx+C.
2. ∫(x2+2) dx∫(x2+2)dx

Split the integral into two parts:
∫x2 dx+∫2 dx
∫x2dx+∫2dx

    For ∫x2 dx∫x2dx, apply the power rule: x333x3​.
    For ∫2 dx∫2dx, the integral of a constant is the constant times the variable, so 2x2x.
    Solution: x33+2x+C3x3​+2x+C.

3. ∫2sin⁡(x) dx∫2sin(x)dx

Factor out the constant 22:
2∫sin⁡(x) dx
2∫sin(x)dx

The integral of sin⁡(x)sin(x) is −cos⁡(x)−cos(x), so the result is:
Solution: −2cos⁡(x)+C−2cos(x)+C.
4. ∫3x dx∫x3​dx

Factor out the constant 33:
3∫1x dx
3∫x1​dx

The integral of 1xx1​ is ln⁡∣x∣ln∣x∣:
Solution: 3ln⁡∣x∣+C3ln∣x∣+C.
5. ∫1x2 dx∫x21​dx

Rewrite 1x2x21​ as x−2x−2 and use the power rule:
∫x−2 dx=x−1−1=−1x
∫x−2dx=−1x−1​=−x1​

Solution: −1x+C−x1​+C.
6. ∫(13x4−5) dx∫(31​x4−5)dx

Split the integral into two parts:
∫13x4 dx−∫5 dx
∫31​x4dx−∫5dx

    For ∫13x4 dx∫31​x4dx, apply the power rule: x51515x5​.
    For ∫5 dx∫5dx, the result is 5x5x.
    Solution: x515−5x+C15x5​−5x+C.

7. ∫(sin⁡2(x)+cos⁡2(x)) dx∫(sin2(x)+cos2(x))dx

Use the identity sin⁡2(x)+cos⁡2(x)=1sin2(x)+cos2(x)=1.
∫(sin⁡2(x)+cos⁡2(x)) dx=∫1 dx
∫(sin2(x)+cos2(x))dx=∫1dx

Solution: x+Cx+C.
8. ∫(5sin⁡(x)+3ex) dx∫(5sin(x)+3ex)dx

Split the integral into two parts:
5∫sin⁡(x) dx+3∫ex dx
5∫sin(x)dx+3∫exdx

    The integral of sin⁡(x)sin(x) is −cos⁡(x)−cos(x), so −5cos⁡(x)−5cos(x).
    The integral of exex is exex, so 3ex3ex.
    Solution: −5cos⁡(x)+3ex+C−5cos(x)+3ex+C.

9. ∫x3 dx∫3x
​dx

Rewrite x33x

​ as x1/3x1/3 and apply the power rule:
∫x1/3 dx=x4/34/3=34x4/3
∫x1/3dx=4/3x4/3​=43​x4/3

Solution: 34x4/3+C43​x4/3+C.
10. ∫10x dx∫10x
​dx

Rewrite 10x10x
​ as 10⋅x1/210
​⋅x1/2 and factor out 1010

​:
10∫x1/2 dx=10⋅x3/23/2=2103x3/2
10
​∫x1/2dx=10
​⋅3/2x3/2​=3210
​​x3/2

Solution: 2103x3/2+C3210

​​x3/2+C.
11. ∫cos⁡(52x+3) dx∫cos(25​x+3)dx

Let u=52x+3u=25​x+3, so du=52dxdu=25​dx or dx=25dudx=52​du:
∫cos⁡(52x+3) dx=25∫cos⁡(u) du=25sin⁡(u)+C
∫cos(25​x+3)dx=52​∫cos(u)du=52​sin(u)+C

Substitute back uu:
Solution: 25sin⁡(52x+3)+C52​sin(25​x+3)+C.
12. ∫cos⁡(ln⁡(x))x dx∫xcos(ln(x))​dx

Let u=ln⁡(x)u=ln(x), so du=1xdxdu=x1​dx:
∫cos⁡(ln⁡(x))x dx=∫cos⁡(u) du=sin⁡(u)+C
∫xcos(ln(x))​dx=∫cos(u)du=sin(u)+C

Substitute back uu:
Solution: sin⁡(ln⁡(x))+Csin(ln(x))+C.
13. ∫xln⁡(x) dx∫xln(x)dx

Use integration by parts: let u=ln⁡(x)u=ln(x), dv=x dxdv=xdx, so du=1xdxdu=x1​dx, v=x22v=2x2​:
∫xln⁡(x) dx=x22ln⁡(x)−∫x22⋅1x dx=x22ln⁡(x)−x24
∫xln(x)dx=2x2​ln(x)−∫2x2​⋅x1​dx=2x2​ln(x)−4x2​

Solution: x22ln⁡(x)−x24+C2x2​ln(x)−4x2​+C.
14. ∫xex dx∫xexdx

Use integration by parts: let u=xu=x, dv=exdxdv=exdx, so du=dxdu=dx, v=exv=ex:
∫xex dx=xex−∫ex dx=xex−ex
∫xexdx=xex−∫exdx=xex−ex

Solution: xex−ex+Cxex−ex+C.
