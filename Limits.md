# Limits
***



<pre>

</pre>
## Introduction
*https://en.wikipedia.org/wiki/Limit_(mathematics)*\
*https://www.khanacademy.org/math/ap-calculus-ab/ab-limits-new/ab-1-2/a/limits-intro*
***
***Limit:***
the **value** that a **function** (or sequence) **approaches** as the input (or index) approaches some value.
- Does not actually have to attain value. Just has to approach it.

$$
{lim\atop x\rightarrow \Box}f(x)=\Box
$$



<pre>

</pre>
## Limit Laws
***
$$
{lim\atop x\rightarrow a}kf(x)\quad=\quad k\left[{lim\atop x\rightarrow a}f(x)\right]
$$

<pre></pre>
$$
{lim\atop x\rightarrow a}\left[f(x)\pm g(x)\right]\quad=\quad\left[{lim\atop x\rightarrow a}f(x)\right]\pm\left[{lim\atop x\rightarrow a}g(x)\right]
$$

<pre></pre>
$$
{lim\atop x\rightarrow a}f(x)g(x)\quad=\quad\left[{lim\atop x\rightarrow a}f(x)\right]\left[{lim\atop x\rightarrow a}g(x)\right]
$$

<pre></pre>
$$
{lim\atop x\rightarrow a}\frac{f(x)}{g(x)}\quad=\quad\frac{{lim\atop x\rightarrow a}f(x)}{{lim\atop x\rightarrow a}g(x)}
$$

<pre></pre>
$$
{lim\atop x\rightarrow a}[f(x)]^n\quad=\quad\left[{lim\atop x\rightarrow a}f(x)\right]^n
$$


<pre>

</pre>
## Ways $x$ can approach $a$
***
### To infinity
$\text{lim }f(x)= \Box$  
$x\rightarrow \infty$

When $x$ approaches infinity, things that do not effect the equation when approaching infinity can be ignored. This is what 

<pre></pre>
$$
\begin{flalign}
\frac{x^{a+1}}{x^a} &&
\end{flalign}
$$
- Approaches infinity
- Note: the exponent on the numerator does not need to be $a+1$,  it just needs to be bigger than $a$ on the denominator

<pre></pre>
$$
\begin{flalign}
\frac{ax^c}{bx^c} &&
\end{flalign}
$$
- Approaches $\frac{a}{b}$

<pre></pre>
$$
\begin{flalign}
\frac{x^a}{x^{a+1}} &&
\end{flalign}
$$
- Approaches 0
- Note: the exponent on the denominator does not need to be $a+1$,  it just needs to be bigger than $a$ on the numerator.

<pre>

</pre>
### To a number from negative
$\text{lim }f(x)= \Box$  
$x\rightarrow a^-$
- $x$ gets extremely close to $a$ from the negative side but never reaches it, so $x=a-0.\bar{0}1$

> Ex:
> $$
> {lim\atop x\rightarrow2^-}(\frac{5}{x-2})=-\infty
> $$
> 
> $x$ looks like $1.\bar9$ so: $\frac{5}{1.\bar{9}-2}=\frac{5}{-0.\bar{0}1}=-\infty$
> 
> <iframe src="https://www.desmos.com/calculator/vqxxybuvhg?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
### To a number from positive
$\text{lim }f(x)= \Box$  
$x\rightarrow a^+$
- $x$ gets extremely close to $a$ from the positive side but never reaches it, so $x=a+0.\bar{0}1$

> Ex:
> $$
> {lim\atop x\rightarrow2^+}(\frac{5}{x-2})=\infty
> $$
> 
> $x$ looks like $2.\bar01$ so: $\frac{5}{2.\bar{0}1-2}=\frac{5}{0.\bar{0}1}=\infty$
> 
> <iframe src="https://www.desmos.com/calculator/vqxxybuvhg?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
### To a number from both sides
$\text{lim }f(x)= \Box$  
$x\rightarrow a$

This can only be solved if the graph approaches the same point from both sides at $a$:

> Ex:
> $$
> {lim\atop x\rightarrow2}(x^2)=4
> $$
> - It is approaching $4$ from both sides
> 
> <iframe src="https://www.desmos.com/calculator/lypyagze9b?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>


> Ex2:
> ${lim\atop x\rightarrow0}(\frac{1}{x})=DNE$
> - The graph goes to both $+\infty$ and $-\infty$ and not to one point. When this happens the limit does not exist ($DNE$)
> 
> <iframe src="https://www.desmos.com/calculator/5gnt45d216?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>


<pre>

</pre>
## Finding limits:
***
### Graphically
#### Solving
Look at the graph

<pre></pre>
#### Cases

<u>**No value at what x is approaching**</u>
- The graph does not need to have a value at the point that $x$ is approaching.
- The graph has to be continuous

> Ex1:
> $$
> {lim\atop x\rightarrow5}f(x)
> $$
> <iframe src="https://www.desmos.com/calculator/3hrcjijm5g?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> The limit would be equal to $5$ even through $f(5)=2$. This is because the limit approaches $5$ but does not reach it 

> Ex2:
> $$
> {lim\atop x\rightarrow5}f(x)
> $$
> <iframe src="https://www.desmos.com/calculator/a5ftt5vzwu?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> The limit does not exist ($\text{DNE}$)

<pre></pre>
<u>**Approaching from one side**</u>\
[[Limits#To a number from negative]]\
[[Limits#To a number from positive]]
- The graph does not need to have a value at the point that $x$ is approaching.
- The graph does not have to be continuous

> Ex1:
> $$
> {lim\atop x\rightarrow5^+}f(x)
> $$
> <iframe src="https://www.desmos.com/calculator/a5ftt5vzwu?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> Approaching $5$ from the positive side would give a limit of $2$

> Ex2:
> $$
> {lim\atop x\rightarrow5^-}f(x)
> $$
> <iframe src="https://www.desmos.com/calculator/a5ftt5vzwu?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> Approaching $5$ from the positive side would give a limit of $5$



<pre></pre>
### Algebraically
#### Solving
<u>**Substitution**</u>
- Replace $x$ in the equation to what $x$ is approaching. This only works if there are no divide by $0$ errors.

If you run into a divide by $0$ error, you must simplify

> $$
> {lim\atop x\rightarrow 2}f(x)=\frac{x^2+3}{x+1}=\frac{2^2+3}{2+1}=\frac{7}{3}
> $$


<pre></pre>
<u>**Factoring/Simplifying**</u>
- Difference of squares
$$
a^2-b^2=(a-b)(a+b)
$$

- Difference of cubes
$$
a^3-b^3=(a-b)(a^2+ab+b^2)
$$

- Sum of cubes
$$
a^3+b^3=(a+b)(a^2-ab+b^2)
$$

<pre></pre>
<u>**Conjugates**</u>
1. Find conjugate to what you want to rationalize
	- A math conjugate is formed by changing the sign between two terms in a binomial.
	- Ex: Conjugate of $x-y$ is $x+y$
2. Only multiply out the side you want to rationalize
3. Profit

> Ex: Rationalizing denominator
> $$
> \begin{align}
> {lim\atop x\rightarrow0}&\frac{3-\sqrt{x+9}}{x} \\
> {lim\atop x\rightarrow0}&\frac{3-\sqrt{x+9}}{x}\cdot\frac{3+\sqrt{x+9}}{3+\sqrt{x+9}} \\
> {lim\atop x\rightarrow0}&\frac{9-(x+9)}{x(3+\sqrt{x+9})} \\
> {lim\atop x\rightarrow0}&\frac{-1}{(3+\sqrt{x+9})}=-\frac{1}{6} \\
> \end{align}
> $$

<pre></pre>
#### Cases
<u>**Absolute functions**</u>\
[[Limits#To a number from negative]]\
[[Limits#To a number from positive]]
- You have to take both cases of the absolute function

$$
|f(x)|
$$

$$
\begin{equation*}
f(x)=\begin{cases}
          f(x) \quad \quad \quad \quad f(x)\geq0 \\
          -f(x) \quad \quad \quad f(x<0 \\
     \end{cases}
\end{equation*}
$$


> Ex:
> $$
> \begin{align}
> {lim\atop x\rightarrow3}&\frac{|x-3|}{x-3} \\
> \end{align}
> $$
> $$
> \begin{equation*}
> |x-3|=\begin{cases}
>           x-3 \quad \quad \quad \quad x-3\geq0 \\
>           -(x-3) \quad \quad \quad x-3<0 \\
>      \end{cases}
> \end{equation*}
> $$
> $$
> \begin{align}
> {lim\atop x\rightarrow3^+}&\frac{x-3}{x-3}=1 \\
> {lim\atop x\rightarrow3^-}&\frac{-(x-3)}{x-3}=-1 \\
> \end{align}
> $$
> 
> Because both sides do not meet up the graph is discontinuous and the limit therefore $\text{DNE}$

<pre></pre>
<u>**Exponential**</u>\
[[Limits#To infinity]]

> Ex2: 
> $$
> {lim\atop x\rightarrow \infty}\left(\frac{4}{3}\right)^x=\infty
> $$

> Ex3:
> $$
> {lim\atop x\rightarrow \infty}\left(\frac{2}{3}\right)^x=0
> $$

<pre></pre>
<u>**Fractions**</u>

> Ex:
> $$
> \begin{align}
> {lim\atop x\rightarrow4} & \frac{\frac{1}{x}-\frac{1}{4}}{x-4} \\
> {lim\atop x\rightarrow4} & \frac{\frac{4}{4}(\frac{1}{x})-(\frac{1}{4})\frac{x}{x}}{x-4} \\
> {lim\atop x\rightarrow4} & \frac{\frac{4}{4x}-\frac{x}{x4}}{x-4} \\
> {lim\atop x\rightarrow4} & \frac{\frac{4-x}{4x}}{x-4} \\
> 	{lim\atop x\rightarrow4} & \frac{-1}{x4}=-\frac{1}{16}
> \end{align}
> $$



<pre>

</pre>
## Piecewise functions
***
- Functions that have multiple pieces

Ex:
$$
\begin{equation*}
g(x)=\begin{cases}
          3 \quad \quad \quad \quad x<1 \\
          x-1 \quad \quad 1\leq x<3 \\
		2 \quad \quad \quad \quad x>3\\
     \end{cases}
\end{equation*}
$$



<pre>

</pre>
## Continuity
***
A continuous graph is a graph that has no
- Gaps
- Holes
- Jumps
- Asymptotes

Discontinuous graphs are 
- Rational functions with NPVs
- Discontinuous piecewise functions
- Trig function (tanx)

<pre></pre>
### Determining continuity in piecewise functions
1. Check to see if all functions are continuous
2. Check to see if each separate function connects to make a continuous graph
	- ${lim\atop x\rightarrow a^-}f(x)={lim\atop x\rightarrow a^+}f(x)=f(a)$

> Ex:
> $$
> \begin{equation*}
> f(x)=\begin{cases}
>           x^2-1 \quad \quad \quad \quad x<1 \\
>           x-1 \quad \quad \quad \quad x>1 \\
> 		1 \quad \quad \quad \quad \quad \quad x=1\\
>      \end{cases}
> \end{equation*}
> $$
> 1. All functions are continuous
> 2. 
> $$
> \begin{align}
> {lim\atop x\rightarrow 1^-}x^2-1&=0 \\
> {lim\atop x\rightarrow 1^+}x-1&=0 \\
> f(1)&=0
> \end{align}
> $$
> 
> It is continuous
> 
> <iframe src="https://www.desmos.com/calculator/gg6qyqqvwy?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
<pre></pre>
### Creating continuity in graphs
Creating continuity by finding a constant:
1. Discontinuity occurs at the changes between the pieces of the graph, ie the points between the domains of the different peices of the piecewise function
2. Set the limit of the positive and negative side equal to each other
3. Algebraically solve for the missing value


>Ex: Find a value for k so that the function is continuous everywhere
> $$
> \begin{equation*}
> f(x)=\begin{cases}
>           x^2-k \quad \quad \quad \quad x<3 \\
>           2kx \quad \quad \quad \quad \quad x \geq 3  \\
>      \end{cases}
> \end{equation*}
> $$
> Set both sides of the domain restrction equal to each other and then solve algebraically
> $$
> \begin{align}
> {lim\atop x\rightarrow 3^-}f(x)&={lim\atop x\rightarrow 3^+}f(x)& \\
> \end{align}
> $$
> $$
> \begin{align}
> 3^2 - k &= 2k(3) \\
> 9 - k &= 6k \\
> 9 &= 7k \\
> k &= \frac{9}{7}
> \end{align}
> $$

Creating continuity by filling points of discontinuity:
1. Simplify the fucntion and eliminate the factor that is causing the error leading to the POD
2. Calculate the corresponding y coordinate
3. Write a new piecewise function including an assigned value for the POD
>Ex: Define f(3) so that f(x) is continuous
> $$
> \begin{align}
> f(x) &= \frac{x^2 - 8x +15}{x - 3} \\
> &= \frac{(x - 5)(x - 3)}{x - 3} \\
> &= x-5
> \end{align}
> $$
> <pre></pre>
> $$
> \begin{align}
> f(3) &= 3-5 \\
> &= -2 \\
> POD &= (3,-2)
> \end{align}
> $$
> $$
> \begin{equation*}
> f(x)=\begin{cases}
>           \frac{x^2 - 8x +15}{x - 3} \quad \quad \quad \quad x \ne 3 \\
>           -2 \quad \quad \quad \quad \quad \quad  x = 3  \\
>      \end{cases}
> \end{equation*}
> $$

<pre>

</pre>
## Trig
***
$$
{lim\atop x\rightarrow0}sin(x) = 0
$$

<pre></pre>
$$
{lim\atop x\rightarrow0}cos(x) = 1
$$

<pre></pre>
$$
{lim\atop x\rightarrow0}tan(x) = 0
$$

<pre></pre>
$$
{lim \atop x\rightarrow 0} \frac{\text{sin}(x)}{x} = 1
$$

<pre></pre>
$$
{lim \atop x\rightarrow 0} \frac{1 -\text{cos}(x)}{x} = 0
$$
* Where $x$ is any number




<pre>

</pre>
## Addenda
***
### Equivalence
It is important to remember that 
$$
{lim\atop x\rightarrow a}f(x)\neq f(x)
$$

<pre></pre>
### Change $x\rightarrow a$
$$
{lim \atop x\rightarrow a}f(x) = {lim \atop x-a\rightarrow 0}f(x)
$$