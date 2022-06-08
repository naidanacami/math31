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
###### Ex3: