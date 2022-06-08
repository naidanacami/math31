# Graphing
We can use derivatives to graph equations by hand:
***
           

<pre></pre>
1. Vertical Asymptotes:
	- When $\frac{f(x)}{g(x)}\text{, }g(x)=0$

<pre></pre>
2. Horizontal asymptotes
	- Where ${lim \atop x\rightarrow\pm\infty}f(x)$

<pre></pre>
3. Domain
	- Polynomial functions: {$x|x\in\mathbb{R}$}
	- Rational functions ($y=\frac{f(x)}{g(x)}$): {$x|g(x)\neq{0}\text{, }x\in\mathbb{R}$}
	- Radical functions $y=\sqrt[n]{f(x)}$
		- If $n$ is **even**: $f(x)\geq 0$
		- If $n$ is **uneven**: {$x|x\in\mathbb{R}$}
		
<pre></pre>
4. Range
	- Radical ($\sqrt[n]{f(x)}$)
		- {$y|f(x)\geq0\text{, }y\in\mathbb{R}$}

<pre></pre>
5. Intercepts
	- $y\text{-int}$ when $x=0$
	- $x\text{-int}$ when $y=0$
		- Factor
		- Quadratic equation

<pre></pre>
6. Asymptotes (if any)
	- $y=\frac{f(x)}{g(x)}$
		- Vertical asymptote: NPV
	- $y=b^x$, $y=\text{log}_bx$
		- Horizontal asymptote ${lim\atop x\to\pm\infty}$

<pre></pre>
7. Max/Min
	- May be a max/min when $y’=0$
		- Values of interest:
			- Values that make $y'=0$
			- NPVs
	- Increase when $y’>0$
	- Decrease when $y’<0$


<pre></pre>
8. Concavity
- $y’’<0$: Concave down
- $y’’>0$: Concave up
- $y’’=0$: Point of inflection



<pre>

</pre>
### Examples:

##### Ex1: Polynomial:
> 
> Graph the graph of : $(x^3-1)^2$
>
> <pre></pre>
> <u>**Vertical Asymptotes:**</u> None
> 
> <pre></pre>
> <u>**Horizontal Asymptotes:**</u> None
>
> <pre></pre>
> <u>**Domain:**</u>
> 
> {$x|x\in\mathbb{R}$}
> 
> - The equation is a polynomial
> <pre></pre>
>
> <u>**Range:**</u>
> Does not help
> 
> <pre></pre>
> <u>**Intercepts**:</u>
> $$
> \begin{align}
> y\text{-int: }y &= ((0)^3-1)^2=1 \\
> x\text{-int: }x &= 0 = (x^3-1)^2=1 \\
> \end{align}
> $$
> 
> <pre></pre>
> <u>**Max/Min:**</u>
> $$
> \begin{align}
> y &= (x^3-1)^2 \\
> y’ &= 2(x^3-1)(3x^2) \\
> y’ &= (6x^2)(x^3-1) \\
> &x=0,\text{ }x=1 \\
> \end{align}
> $$
> ```
> - Use a table when we are not certain which sign the equation will be. 
> - Place point of interest (whatever makes $y'=0$) and use a test point to determine whether each  point will be positive or negative
> ```
> |       |$-1$ |$0$ |$\frac{1}{2}$ |$1$ | $2$ |
> |:---    | :---: | :---: | :---:         |:---:| :---:|
> |$6x^2$ | $+$ |\|  | $+$          |\|  | $+$
> |$x^3-1$| $-$ |\|  | $-$          |\|  | $+$
> |$y'=$  | $-$ |\|  | $-$          |\|  | $+$ |  
> ||$\searrow$||$\searrow$||$\nearrow$
> 
> - This means that the graph will decrease when $x<1$ and increase when $x>1$
> - Since the graph goes down before $x=1$ goes up after, there is a min there
> 
> $$
> \begin{align}
> x &= 1 \\
> y &= (x^3-1)^2 \\ 
> y &= (1^3-1)^2 \\ 
> y &= 0
> \end{align}
> $$
> - There is a min point at $(1,0)$
> 
> <pre></pre>
> <u>**Concavity:**</u>
> $$
> \begin{align}
> y’ &= (6x^2)(x^3-1) \\
> y’ &= 6x^5-6x^2 \\
> y'' &= 30x^4-12x \\
> y'' &= 6x(5x^3-2) \\
> &x=0,\text{ }x=\sqrt[3]{\frac{2}{5}}=0.7 \\
> \end{align}
> $$
> 
> |       |$-1$ |$0$ | $0.5$ |$0.7$ | $1$ |
> |:---    | :---: |:---: | :---:         |:---:| :---:|
> |$6x$ | $-$ |\|  | $+$          |\|  | $+$
> |$5x^3-2$| $-$ |\|  | $-$          |\|  | $+$
> |$y''=$  | $+$ |\|  | $-$          |\|  | $+$ |  
> 
> - Curves up when $x<0$, $x>1$
> - Curves down when $0<x<0.7$
> - Point of inflection when $x=0$, $x=0.7$
> 
> $$
> \begin{align}
> x &= 0 \\
> y &= (0^3-1)^2=1 \\ 
> \\
> x &= 0.7 \\
> y &= (0.7^3-1)^2=0.36 \\ 
> \end{align}
> $$
> 
> <iframe src="https://www.desmos.com/calculator/04qbdxrves?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
##### Ex2: Rational:

> Graph the graph of : $\frac{x^2}{1-x^2}$
> 
> <pre></pre>
> <u>**Vertical Asymptotes:**</u> 
> $$
> \begin{align}
> 1-x^2 &\neq 0 \\
> -x^2 &\neq -1 \\
> x^2 &\neq 1 \\
> x &\neq \pm\sqrt{1} \\
> x &\neq \pm1
> \end{align}
> $$
> - VA at $x=\pm1$
> 
> <pre></pre>
> <u>**Horizontal Asymptotes:**</u>
> $$
> \begin{align}
> {lim\atop x\rightarrow +\infty} \frac{x^2}{1-x^2} = -1 \\ 
> {lim\atop x\rightarrow -\infty} \frac{x^2}{1-x^2} = -1 \\ 
> \end{align}
> $$
> - HA at $y=-1$
> 
> <pre></pre>
> <u>**Domain:**</u>
> $$
> \begin{align}
> 1-x^2 &\neq 0 \\
> -x^2 &\neq -1 \\
> x^2 &\neq 1 \\
> x &\neq \sqrt{1} \\
> x &\neq \pm1
> \end{align}
> $$
> - {$x|x\neq\pm1\text{, }x\in\mathbb{R}$}
> - The equation is a rational
> 
> <pre></pre>
> <u>**Range:**</u>
> Does not help 
> 
> <pre></pre>
> <u>**Intercepts**:</u>
> $$
> \begin{align}
> y\text{-int: }y &= \frac{0^2}{1-0^2}=0 \\
> x\text{-int: }x &= 0 = \frac{x^2}{1-x^2}=0 \\
> \end{align}
> $$
> 
> <pre></pre>
> <u>**Max/Min:**</u>
> $$
> \begin{align}
> y &= \frac{x^2}{1-x^2} \\
> y’ &= \frac{(1-x^2)(2x)-(x^2)(-2x)}{(1-x^2)^2} \\
> y’ &= \frac{(2x-2x^3)+2x^3}{(1-x^2)^2} \\
> y’ &= \frac{2x}{(1-x^2)^2} \\
> x &= 0
> \end{align}
> $$
> 
> ```
> - Use a table when we are not certain which sign the equation will be. 
> - Place point of interest (whatever makes $y'=0$) and use a test point to determine whether each  point will be positive or negative
> ```
> - We use $x=0$ since it makes $y'=0$. We also use $\pm1$ because they are NPVs
> 
> |                       |$-2$ |$-1$  |$-0.5$|  $0$ |$0.5$|$1$ | $2$ |
> |:---                  | :---:|  :---:  |:---:     | :---: | :---:   |:---:| :---:|
> |$2x$               | $-$  | \|       |   $-$   |  \|    |  $+$   |\|     | $+$
> |$(1-x^2)^2$| $+$  |\|        |   $+$   | \|     | $+$    |\|     | $+$
> |$y'=$             | $-$  |\|        | $-$     | \|     |  $+$   |\|     | $+$ |  
> ||$\searrow$||$\searrow$||$\nearrow$||$\nearrow$
> 
> - $\searrow$ when $x<0$
> - $\nearrow$ when $x>0$
> - Min at $x=0$
>
> $$
> \begin{align}
> x &= 0 \\
> y &= \frac{x^2}{1-x^2} \\ 
> y &= \frac{0^2}{1-0^2} \\ 
> y &= 0
> \end{align}
> $$
> - There is a min point at $(0,0)$
> 
> <pre></pre>
> <u>**Concavity:**</u>
> $$
> \begin{align}
> y’ &= \frac{2x}{(1-x^2)^2} \\
> y'' &= \frac{(1-x^2)^2(2)-(2x)2(1-x^2)(-2x)}{(1-x^2)^4} \\
> y'' &= \frac{(1-x^2)(2)(1-x^2+4x^2)}{(1-x^2)^4} \\
> y'' &= \frac{(2)(3x^2+1)}{(1-x^2)^3} \\
> &x=\pm1 \\
> \end{align}
> $$
> 
> |       |$-2$ |$-1$ | $0$ |$1$ | $2$ |
> |---    | --- |--- | ---         |---| ---|
> |$6x^2+2$ | $+$ |\|  | $+$          |\|  | $+$
> |$(1-x^2)^3$| $-$ |\|  | $+$          |\|  | $-$
> |$y''=$  | $-$ |\|  | $+$          |\|  | $-$ |  
> 
> - Curves up when $-1<x<1$
> - Curves down when $x<-1$, $x>1$
> - Point of inflection at $x=-1$, $x=1$
> 
> $$
> \begin{align}
> x &= -1 \\
> y &= \text{NPV} \\
> \\
> x &= 1 \\
> y &= \text{NPV} \\
> \end{align}
> $$
> 
> <iframe src="https://www.desmos.com/calculator/wlndq3vtas?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
##### Ex3: Radical:

> Graph the graph of : $\sqrt{4-x^2}$
> 
> <pre></pre>
> <u>**Domain:**</u>
> $$
> \begin{align}
> 4-x^2 &\geq 0 \\
> -(x^2-4) &\geq 0 \\
> -(x+2)(x-2) &\geq 0 \\
> \end{align}
> $$
> $x=\pm2$ are zeroes. We have to find out where around the zeros the expression will become negative:
> 
> |               |$-3$ |$-2$  |$0$|  $2$ |$3$|
> |:---         | :---:|  :---:  |:---:     | :---: | :---:   |
> |$-1$      | $-$  | \|       |   $-$   |  \|    |  $-$   |
> |$(x+2)$| $-$  |\|        |   $+$   | \|     | $+$    |
> |$(x-2)$| $-$  |\|        |   $-$   | \|     | $+$    |
> |$y'=$    | $-$  |\|        | $+$     | \|     |  $-$   |
> $4-x^2 \geq 0$ when $-2\leq x\leq2$ therefore the domain is:
> $$
\{x|-2\leq x \leq 2, x\in\mathbb{R}\}
> $$
> 
> <pre></pre>
> <u>**Range:**</u>
> since $\sqrt{f(x)}$ can never be negative:
> 
> {$y|y\geq0, y\in\mathbb{R}$}
> 
> <pre></pre>
> <u>**Intercepts**:</u>
> $$
> \begin{align}
> y\text{-int: }y &= \sqrt{4-0^2}=2 \\
> x\text{-int: }x &= 0 = \sqrt{4-x^2} \\
> 0 &= 4-x^2 \\
> x^2 &= 4 \\
> x &= \pm\sqrt4 = \pm 2 \\
> \end{align}
> $$
> 
> <pre></pre>
> <u>**Max/Min:**</u>
> $$
> \begin{align}
> y &= \sqrt{4-x^2} \\
> y &= (4-x^2)^{\frac{1}{2}} \\
> y’ &= \frac{1}{2}(4-x^2)^{-\frac{1}{2}}(-2x) \\
> y’ &= -x(4-x^2)^{-\frac{1}{2}} \\
> y’ &= \frac{-x}{\sqrt{4-x^2}} \\
> x &= 0
> \end{align}
> $$
> 
> ```
> - Use a table when we are not certain which sign the equation will be. 
> - Place point of interest (whatever makes $y'=0$) and use a test point to determine whether each  point will be positive or negative
> ```
> - We use $x=0$ since it makes $y'=0$. We also use $\pm2$ because it makes the denominator $0$*. Remember the domain ($\{x|-2\leq x \leq 2, x\in\mathbb{R}\}$
> 
> |                             |$-3$ |$-2$  |$-1$|  $0$ |$1$|$2$ | $3$ |
> |:---                        | :---:|  :---:  |:---:     | :---: | :---:   |:---:| :---:|
> |$-x$                     | #  | \|       |   $+$   |  \|    |  $-$   |\|     | #
> |$\sqrt{4-x^2}$| #  |\|        |   $+$   | \|     | $+$    |\|     | #
> |$y'=$                   | #  |\|        | $+$     | \|     |  $-$   |\|     | # 
> ||||$\nearrow$||$\searrow$||
> 
> - $\searrow$ when $x<0$
> - $\nearrow$ when $x>0$
> - Min at $x=0$
>
> $$
> \begin{align}
> x &= 0 \\
> y &= \sqrt{4-x^2} \\ 
> y &= \sqrt{4-0^2} \\ 
> y &= 2
> \end{align}
> $$
> - There is a max point at $(0,2)$
> 
> <pre></pre>
> <u>**Concavity:**</u>
> $$
> \begin{align}
> y’ &= \frac{-x}{\sqrt{4-x^2}} \\
> y'' &= \frac{(4-x^2)^{\frac{1}{2}}(-1)-(-x)\frac{1}{2}(4-x^2)^{-\frac{1}{2}}(-2x)}{4-x^2} \\
> y'' &= \frac{(4-x^2)^{-\frac{1}{2}}(-4)}{4-x^2} \\
> y'' &= \frac{-4}{\sqrt{4-x^2}(4-x^2)} \\
> \end{align}
> $$
> We use $\pm2$ because it makes the denominator $0$*. Remember the domain ($\{x|-2\leq x \leq 2, x\in\mathbb{R}\}$
> 
> |       |$-3$ |$-2$ | $0$ |$2$ | $3$ |
> |---    | --- |--- | ---         |---| ---|
> |$-4$ | # |\|  | $-$          |\|  | #
> |$\sqrt{4-x^2}$ | # |\|  | $+$          |\|  | #
> |$4-x^2$| # |\|  | $+$          |\|  |#
> |$y''=$  | # |\|  | $-$          |\|  |# |  
> 
> - Curves down when $-2<x<2$
> 
> <iframe src="https://www.desmos.com/calculator/lkbqvehh3j?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

<pre>

</pre>
##### Ex4: Trig:
> Graph the graph of $y=x-\cos(x)$, $x\Bigg|0\leq x\leq2\pi$
> 
> <pre></pre>
> <u>**Domain**</u>
> $$
> x\Bigg|0\leq x\leq2\pi
> $$
> 
> <pre></pre>
> <u>**Intercepts:**</u>
> $$
> \begin{align}
> y\text{-int: }y &= 0-\cos(0) = -1\\
> x\text{-int: }x &= 0 = \sqrt{4-x^2} \\
> x &= \cos(x) \\
> \end{align}
> $$
> - $x=\cos(x)$ is algebraically difficult.
> 
> <pre></pre>
> <u>**Max/Min:**</u>
> $$
> \begin{align}
> y' &= 1+\sin(x)=0 \\
> x &= \frac{3\pi}{2}
> \end{align}
> $$
> 
> ||$0$||$\frac{3\pi}{2}$||$2\pi$|
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |$1+\sin(x)$|\||$+$|\||$+$|\||
> |$y'=$|\||$+$|\||$+$|\||
> - $f(x)$ is always increasing
> 
> <pre></pre>
> <u>**Concavity**</u>
> $$
> \begin{align}
> y'' &= \cos(x) = 0 \\
> x &= \frac{\pi}{2},\frac{3\pi}{2}
> \end{align}
> $$
> ||$0$||$\frac{\pi}{2}$||$\frac{3\pi}{2}$||$2\pi$|
> |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
> |$\cos(x)$|\||$+$|\||$-$|\||$+$|\||
> |$y''=$|\||$+$|\||$-$|\||$+$|\||
> - Point of inflection at $x=\frac{\pi}{2}, \frac{3\pi}{2}$
> $$
> \begin{align}
> x &= \frac{\pi}{2} \\
> y &= \frac{\pi}{2}-\cos(\frac{\pi}{2}) \\
> y &= \frac{\pi}{2} \\
> \\
> x &= \frac{3\pi}{2} \\
> y &= \frac{3\pi}{2}-\cos(\frac{3\pi}{2}) \\
> y &= \frac{3\pi}{2} \\
> \\
> (\frac{\pi}{2}, \frac{\pi}{2})&;\quad(\frac{3\pi}{2}, \frac{3\pi}{2})
> \end{align}
> $$
> 
> <iframe src="https://www.desmos.com/calculator/q53brmogx6?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>


<pre>

</pre>
##### Ex5: Natural Log:
> Graph the graph of $y=ln(4-x^2)$
> 
> <pre></pre>
> <u>**Domain:**</u>
> $$
> \begin{align}
> 4-x^2 &> 0 \\
> (2-x)(2+x) &> 0 \\
> x &= \pm2
> \end{align}
> $$
> 
> |||$-2$||$2$||
> |:---:|:---:|:---:|:---:|:---:|:---:|
> |$2-x$|$+$|\||$+$|\||$-$|
> |$2+x$|$-$|\||$+$|\||$+$|
> ||$-$|\||$+$|\||$-$|
> $$
> -2<x<2
> $$
> 
> <pre></pre>
> <u>**Intercepts:**</u>
> $$
> \begin{align}
> y\text{-int: }y &= ln(4-0^2) = ln(4) = ~1.39\\
> x\text{-int: }x &= 0 = ln(4-x^2)\\
> e^0 &= 4-x^2 \\
> 3 &= x^2 \\
> \pm\sqrt3 &= x = ~\pm1.7 \\
> \end{align}
> $$
> 
> <pre></pre>
> <u>**Max\Min:**</u>
> $$
> \begin{align}
> y' &= \frac{-2x}{4-x^2} = 0 \\
> x &= 0
> \end{align}
> $$
> 
> ||#|$-2$||$0$||$2$||
> |:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
> |$-2x$|#|\||$-$|\||$+$|\||#|
> |$4-x^2$|#|\||$-$|\||$-$|\||#|
> |$y'=$|#|\||$+$|\||$-$|\||#|
> ||#|\||$\nearrow$|\||$\searrow$|\||#|
> - Max at $x=0$
> $$
> \begin{align}
> y &= ln(4-0^2) \\
> y &= ln(4) \\
> \end{align}
> $$
> 
> <pre></pre>
> <u>**Concavity:**</u>
> $$
> \begin{align}
> y'' &= \frac{(4-x^2)(-2)-(-2x)(-2x)}{(4-x^2)^2} \\
> 0 &= \frac{-8+2x^2-4x^2}{(4-x^2)^2} \\
> 0 &= \frac{-2x^2-8}{(4-x^2)^2} \\
> &\frac{-}{+}
> \end{align}
> $$
> - Always concave down
> 
> <iframe src="https://www.desmos.com/calculator/7wprrcdks0?embed" width="500" height="500" style="border: 1px solid #ccc" frameborder=0></iframe>

