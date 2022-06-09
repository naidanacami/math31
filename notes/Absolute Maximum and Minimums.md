# Absolute Maximum and Minimums
*https://www.khanacademy.org/math/ap-calculus-ab/ab-diff-analytical-applications-new/ab-5-5/a/absolute-minima-and-maxima-review*
***
An absolute maximum/minimum is the lowest/highest point on the graph
<iframe src="https://www.desmos.com/calculator/rogovsibbo?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>
<pre></pre>

Domain has to be taken into account too:

While the graph $y=x$ does not have any max/min, when we give it the domain of $\{x|-5\geq x\geq 5\}$, we have to pay attention to the end behavior:
<iframe src="https://www.desmos.com/calculator/zvo91791ju?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>



<pre>

</pre>
### Finding absolute max/mins algebraically
***
1. Get zeroes of derivative
2. Get $y$ values of the zeroes and of the restricted domain (if applicable)
3. The lowest/highest $y$ values are the absolute max/min

> Ex1:
> Get the absolute max and min 
> $$
> y=x^3-3x^2-24x+32
> $$
> $$
> \{x|-1\leq x \leq 6\}
> $$
> 
> <pre></pre>
> 1. Get zeroes of derivative
> $$
> \begin{align}
> y &= x^3-3x^2-24x+32 \\
> y' &= 3x^2-6x-24 \\
> y' &= 3(x^2-2x-8) \\
> y' &= 3(x+2)(x-4) \\
> & x=-2\text{, }x=4
> \end{align}
> $$
> $x=-2$ is not in our domain so we do not include it:
> 
> <pre></pre>
> 2. Get $y$ values of the zeroes and of the restricted domain (if applicable)
> 
> |x|y|
> | :---: | :---: |
> | -1 | 52 |
> | 4 | -48 |
> | 6 | -4 |
> 
> <pre></pre>
> In this case:
> - $(-1,52)$ is the **absolute max**
> - $(4,-48)$ is the **absolute min**
> 
> <iframe src="https://www.desmos.com/calculator/amqoox9hrx?embed" width="250" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>