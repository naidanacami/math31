# Implicit Differentiation
***
So far, all of the functions we worked with were expressed explicitly in terms of $x$. The dependence of $y$ on $x$ were made explicit.

Ex:
$$
\begin{align}
y &= x^2+5x-3\\
y' &= 2x+5\\
\end{align}
$$

<pre>
</pre>
Sometimes, it is **inconvenient** or **impossible** to find the <u>explicit relationship</u> between $x$ and $y$

In these cases, we find the derivative of **both** sides of the equation with respect to $x$ and then we solve for the term $y'$ that results from taking the derivative of a term with $y$ in it

$\frac{d()}{dx}$ means "take the derivative"

Example: Find $y'$ given that $xy=y+5$

>**Method 1**: In this case, it is possible to solve for $y$ first:
>$$
\begin{align}
xy-y &= 5 \\
y(x-1) &= 5 \\
y &= \frac{5}{x-1} \\
&= 5(x-1)^{-1} \\
y' &= -5(x-1)^{-2} = \frac{-5}{(x-1)^2}
\end{align}
>$$

>**Method 2**: Find the derivative implicitly, differentiating each term with respect to $x$.
>$$
\begin{align}
\frac{d(xy)}{dx} &= \frac{d(y)}{dx}+\frac{d(5)}{dx} \\
x\frac{d(y)}{dx}+y\frac{d(x)}{dx} &= \frac{d(y)}{dx}+0 \\
xy'+y(1) &= y' \\
xy'+y' &= -y \\
y'(x-1) &= -y \\
y' &= \frac{-y}{x-1} \\ 
\text{replace }y&\text{ because we know }y: \\
y' &= \frac{-5}{(x-1)^2} \\ 
\end{align}
>$$
>**NOTE**: you will not always be able to get your derivative as a function of just $x$ 

<pre></pre>
#### Examples:
>Example: Find the derivative of $3x^2y-xy^2=6$
>$$
\begin{align}
\frac{d(3x^2y)}{dx}-\frac{d(xy^2)}{dx} &= \frac{d(6)}{dx} \\
6xy+3x^2y'-(x2yy'+y^2) &= 0 \\
6xy+3x^2y'-2xyy'-y^2 &= 0 \\
3x^2y'-2xyy' &= y^2-6xy \\
y'(3x^2-2xy) &= y^2-6xy \\
y' &= \frac{y^2-6xy}{3x^2-2xy} \\
\end{align}
>$$

<pre></pre>
>Example: Find the slope to the tangent to $\sqrt{y}=\sqrt{xy}-2\sqrt x$ where $x=4$
>$$
\begin{align}
y^{\frac{1}{2}} &= x^{\frac{1}{2}}y^{\frac{1}{2}}-2x^{\frac{1}{2}} \\
\frac{d(y^{\frac{1}{2}})}{dx} &= \frac{d(x^{\frac{1}{2}}y^{\frac{1}{2}})}{dx} - \frac{d(2x^{\frac{1}{2}})}{dx} \\
(\frac{1}{2}y^{-\frac{1}{2}}y')\cdot2 &= (x^{\frac{1}{2}}\frac{1}{2}y^{-\frac{1}{2}}y'+y^{\frac{1}{2}}\frac{1}{2}x^{-\frac{1}{2}}-x^{-\frac{1}{2}})\cdot2 \\
y^{-\frac{1}{2}}y'-x^{\frac{1}{2}}y^{-\frac{1}{2}}y' &= y^{\frac{1}{2}}x^{-\frac{1}{2}}-2x^{-\frac{1}{2}} \\
y'(y^{-\frac{1}{2}}-x^{\frac{1}{2}}y^{-\frac{1}{2}}) &= y^{\frac{1}{2}}x^{-\frac{1}{2}}-2x^{-\frac{1}{2}} \\
y' &= \frac{y^{\frac{1}{2}}x^{-\frac{1}{2}}-2x^{-\frac{1}{2}}}{y^{-\frac{1}{2}}-x^{\frac{1}{2}}y^{-\frac{1}{2}}} \\
&= \frac{x^{-\frac{1}{2}}(y^{\frac{1}{2}}-2)}{y^{-\frac{1}{2}}(1-x^{\frac{1}{2}})} \\
&= \frac{\sqrt y(\sqrt y-2)}{\sqrt x(1-\sqrt x)} \\
y'|_{x=4} &= \frac{\sqrt y(\sqrt y-2)}{\sqrt 4(1-\sqrt 4)} \\
y'|_{x=4} &= \frac{\sqrt y(\sqrt y-2)}{-2} \\
\end{align}
>$$
>NOTE: we must find out what $y$ is and plug it into the derivative
>$$
\begin {align}
\sqrt{y} &= \sqrt{4y}-2\sqrt 4 \\
\sqrt y &= 2\sqrt y-4 \\
4 &= \sqrt y \\
y &= 16\\
y'|_{x=4} &= \frac{\sqrt{16}(\sqrt{16}-2)}{-2} \\
y'|_{x=4} &= \frac{4(4-2)}{-2} \\
y'|_{x=4} &= \frac{8}{-1}\\
y'|_{x=4} &= -4 \\
\end{align}
>$$

>Examples: Implicit differentiation with trig functions
><pre></pre>
>I) $sin(y) = cos(x)$
>$$
>\begin{align}
>cos(y)y' &= -sin(x) \\
>y' &= \frac{-sin(x)}{cosy(y)}
>\end{align}
>$$
><pre></pre>
>II) $3tan(y) = y^4 - sin(x)$
>$$
>\begin{align}
>3sec^2(y)y' &= 4y^3y' - cos(x) \\
>3sec^2(y)y' - 4y^3y' &= - cos(x) \\
>y'[3sec^2(y)- 4y^3] &= - cos(x) \\
>y' &= \frac{- cos(x)}{3sec^2(y)- 4y^3}
>\end{align}
>$$

^404749
