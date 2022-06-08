# Optimization
***
1. Use the information in the problem to write an equation for the quantity that we are optimizing (only one variable in terms of another)
2. Take derivative
3. Set equal to $0$ and solve
4. Profit


#### Examples

> Ex1:
> A company is laying cable from point $P$ to point $Q$. It costs $130/m to lay cable underground and $260/m to lay cable under water. Make it least expensive and 
> round to the nearest tenth.
> 
> <iframe src="https://www.desmos.com/calculator/87ep7wvoqj?embed" width="500" height="175" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> Let $x$ be the base of the triangle. 
> $$
> \begin{align}
> C &= 260(\sqrt{100^2+x^2}+130(1200-x) \\
> C &=130(100^2+x^2)^{-\frac{1}{2}}(2x)-130=0 \\
> 0 &= \frac{260}{\sqrt{100^2+x^2}}-130 \\
> 130(\sqrt{100^2+x^2}) &= 260x \\
> \sqrt{100^2+x^2} &= 2x \\
> 100^2+x^2 &= 4x^2 \\
> 100^2 &= 4x^2-x^2 \\
> 100^2 &= (4-1)x^2 \\
> \sqrt{\frac{100^2}{3}} &= x \\
> x &= 57.7m \\
> \end{align}
> $$


<pre>

</pre>
> Ex2:
> A farmer has $120m$ of fencing. He wants to enclose a rectangular area with a barn on one side and which is divided into 2 sections perpendicular to the barn. What is the largest area the fence can enclose?
> <iframe src="https://www.desmos.com/calculator/7p4ocaqxwi?embed" width="500" height="275" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> In this case, we need a system of equations (otherwise there would be too many variables)
> 
> $$
> \begin{align}
> A &= xy \\
> \\
> 120 &= 3x+y \\
> y &= 120-3x \\
> \\
> A &= x(120-3x) \\
> A &= 120x-3x^2 \\
> A' &= 120-6x = 0 \\
> -120 &= -6x \\
> \frac{-120}{-6} &= x \\
> x &= 20 \\
> A &= x(120-3x) \\
> A &= (20)(120-3(20)) \\
> A &= 1200m^3
> \end{align}
> $$


<pre>

</pre>
> Ex3:
> A Norman window has the shape of a rectangle surmounted by a semicircle. If the Norman window were to have a perimeter of $28ft$, what dimensions would allow the maximum amount of light through the window.
> <iframe src="https://www.desmos.com/calculator/j1mco7bidc?embed" width="200'" height="250" style="border: 1px solid #ccc" frameborder=0></iframe>
> 
> $$
> \begin{align}
> 28 &= \pi r + 2y + 2r \\
> y &= \frac{28-2r-\pi r}{2} \\
> y &= 14-r-\frac{1}{2}\pi r \\
> \\
> A &= \frac{\pi r^2}{2}+2ry \\
> A &= \frac{\pi r^2}{2}+2r(14-r-\frac{1}{2}\pi r) \\
> A &= \frac{\pi r^2}{2}+28r-2r^2-\pi r^2\\
> A' &= \pi r +28-4r-2\pi r=0 \\
> A' &= -\pi r-4r+28=0 \\
> -21 &= r(-4-\pi) \\
> \frac{-21}{-4-\pi} &= r \\
> \\
> y &= 14-r-\frac{1}{2}\pi r \\
> y &= 14-\frac{-21}{-4-\pi}-\frac{-21\pi}{-8-2\pi} \\
> \\
> r &= ~3.9ft \\
> y &= ~3.9ft \\
> \end{align}
> $$