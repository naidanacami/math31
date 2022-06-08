# Anti derivatives
## Notation
***
$\int f(x)dx$
- $\int$: Take the anti derivative of
- $f(x)$: Original function
- $dx$: What variable to change


<pre>

</pre>
## Rules
***
$$
\int x^ndx=\frac{x^{n+1}}{n+1}+c
$$

- Since the derivative of a constant is $0$, we must include $+c$ since that unless we are given more information, we cannot determine $c$

<pre></pre>
$$
\int \text{cos}(x)dx=\frac{\text{sin}(x)}{x'}+c
$$

<pre></pre>
$$
\int \text{sin}(x)dx=-\frac{\text{cos}(x)}{x'}+c
$$

<pre></pre>
$$
\int e^x=\frac{e^x}{x'}+c
$$

<pre></pre>
$$
\int \frac{1}{x}=lnx+c
$$

<pre></pre>
$$
\int f(x)dx-\int g(x)dx = \int f(x)-g(x)dx
$$



<pre>

</pre>
## Area
***
The antiderivative of an equation gives the area from the graph to the x-axis. We have to give it a range.

$$
\int {^A\atop _B}f(x)dx
$$


<pre></pre>
There are 3 cases of graphs:
### Same side of $x$-axis
<iframe src="https://www.desmos.com/calculator/xraqyeavk1?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>

$$
\int {^A\atop _B} f(x)dx\Bigg|{^A\atop _B}f(A)-f(B)=\text{area}
$$

<pre></pre>
### Different side of $x$-axis
<iframe src="https://www.desmos.com/calculator/1cjo9baxl2?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>

$\int$ can give us negative values which indicates a direction. If we calculate it all in one operation, we will not get the right answer. This means that we will have to take the integral for each section. Each section is enclosed by $x$-ints or 1 $x$-int and the domain (found by graphing or factoring)

$$
\Bigg|\int {^A\atop _B} f(x)dx\Bigg| + \Bigg|\int {^B\atop _C} f(x)dx\Bigg|+\Bigg|\int {^D\atop _C} f(x)dx\Bigg|
$$

<pre></pre>
### Area between graphs
<iframe src="https://www.desmos.com/calculator/bum9f1wx2w?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>

We can get the area of $f(x)$ and subtract the area of $g(x)$ to find the area between $f(x)$ and $g(x)$. No need to take absolute. If $g(x)$ on the other side of the $x$-axis from $f(x)$, the areas will add. If $g(x)$ is on the same side, the areas will subtract

$$
\int{^A\atop _B} f(x)dx-\int{^A\atop _B} g(x)dx = \int{^A\atop _B} f(x)-g(x)dx
$$

<pre></pre>
### Addendum
$+c$ does not have to be included because it gets cancelled out
$$
\left[F(A)+\bcancel c\right]-\left[F(B)+\bcancel c\right]
$$



<pre>

</pre>
## Integration by substitution
***
$$
\int g(x)f^{10}(x)dx
$$

Multiplying $f(x)$ out is tedious. We can substitute it. 

**There must be a relation between $f(x)$ and $g(x)$**

> Ex:
> $$
> \int 3x^2(x^3-5)^{12}dx
> $$
> 
> Substitute $x^3-5$ by $u$
> 
> $$
> \int 3x^2u^{12}dx
> $$
> 
> Then
> $$
> \begin{align}
> u &= x^3-5 \\
> \frac{du}{dx} &= 3x^2 \\
> du &= 3x^2dx
> \end{align}
> $$
> 
> We can now substitute in $du$:
> 
> $$
> \int u^{12}du
> $$
> 
> Take anti derivative
> $$
> \int u^{12}du = \frac{u^{13}}{13}+c
> $$
> 
> Substitute $u$
> $$
> \frac{(x^3-5)^{13}}{13}+c
> $$

> Ex2:
> $$
> \begin{align}
> &\int\frac{2x^3+3}{\sqrt{x^4-6x}}dx\\
> \\
> u &= x^4-6x \\
> \frac{du}{dx} &= 4x^3-6 \\
> du &= (4x^3-6)dx \\
> \frac{1}{2}du &= (2x^3-3)dx \\
> \\
> \int u^{-\frac{1}{2}}\frac{1}{2}du &= u^{\frac{1}{2}} \\
> u^{-\frac{1}{2}} &= (x^4-6x)^{\frac{1}{2}}
> \end{align}
> $$