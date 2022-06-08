# Higher Order Derivatives
Since the derivative of every function $f$ is another function $f'$, we can take its derivative too. The result is $f''$ and is called the second derivative of the function.

*https://en.wikipedia.org/wiki/Derivative#Higher_derivatives*
***
$$
y'' = f''(x)=\frac{d^2y}{dx^2}=D^2f(x)=D^2_xf(x)
$$

<pre>
</pre>
>Example: Find the second derivative of $y=-7x^4+5x^3$
>$$
\begin{align}
y &= -7x^4+5x^3 \\
y' &= -28x^3+15x^2 \\
y'' &= -84x^2+30x \\
\end{align}
>$$

<pre>
</pre>
**<u>First Derivative:</u>** the slope of the tangent line to the curve

<pre>
</pre>
**<u>Second Derivative:</u>** tells us how the slope of the tangent line to the graph of $f(x)$ changes as $x$ changes. 
- This  is related to the "type" of curvature we are seeing on the graph

<pre>
</pre>
**<u>Third derivative:</u>** $y'''=f'''(x)=\frac{d^3y}{dx^3}=D^3f(x)$

<pre>
</pre>
**<u>Higher Derivatives:</u>** Beyond the third derivative we stop using the prime notation:
$$
\begin{align}
\text{fourth derivative} &\longrightarrow y^{(4)} \\
\text{fifth derivative} &\longrightarrow y^{(5)} \\
\text{sixth derivative} &\longrightarrow y^{(6)} \\
\end{align}
$$

### Examples
<pre>
</pre>
>Example: Given $y=\frac{x^2}{x-2}$ find $y''$
>$$
\begin{align}
y' &= \frac{2x(x-2)-x^2}{(x-2)^2} \\
&= \frac{2x^2-4x-x^2}{(x-2)^2} \\
&= \frac{x^2-4x}{(x-2)^2} \\
y'' &= \frac{(x-2)^2(2x-4)-(x^2-4x)2(x-2)^2}{(x-2)^4} \\
&= \frac{2\cancel{(x-2)}[(x-2)^2-(x^2-4x)]}{(x-2)^{\cancel{4}3}}\\
&= \frac{2(\cancel{x^2}\bcancel{-4x}+4-\cancel{x^2}\bcancel{+4x})}{(x-2)^3}\\
&= \frac{8}{(x-2)^3}
\end{align}
>$$

<pre>
</pre>
>Example: If $y=5x^3-4x^2+7x-3$, find <u>all</u> higher derivatives
>$$
\begin{align}
y' &= 15x^2-8x+7 \\
y'' &= 30x-8 \\
y''' &= 30 \\
y^{(4)} &= 0 \\
y^{(n)} &= 0\\
\end{align}
>$$

<pre>
</pre>
>Example: Given $2y-y^2=4x$ evaluate $y''$ at $(-2,4)$
>$$
\begin{align}
2y'-2yy' &= 4 \\
y'(2-2y) &= 4 \\
y' &= \frac{4}{2-2y} \\
&= \frac{2}{1-y} \\
&= 2(1-y)^{-1} \\
y'' &= -2(1-y)^{-2}(-1)y' \\
&= \frac{2}{(1-y)^2}y'\\
&= \frac{2}{(1-y)^2}(\frac{2}{1-y})\\
&= \frac{4}{(1-y)^3}\\
y'' |_{(-2,4)} &= \frac{4}{(1-4)^3} = -\frac{4}{27}
\end{align}
>$$