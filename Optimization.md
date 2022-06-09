# Optimization
***
1. Use the information in the problem to write an equation for the quantity that we are optimizing (only one variable in terms of another)
2. Take derivative
3. Set equal to $0$ and solve
4. Profit


#### Examples

> Ex: Triangles
> 
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
> Ex: Fencing
> 
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
> Ex: Composite shape
> 
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



<pre>

</pre>
> Ex: Profit
> 
> A landlord is able to rent out all $60$ units when rent is $\$470$. Every $\$20$ increase in rent causes the loss of $2$ renters. In addition, it costs $\$30$ per month per occupied unit. What should rent be to maximize profits?
> 
> The equation for revenue and profit:
> $$
> \begin{align}
> \text{Revenue} &= \$(\#) \\
> \text{Profit} &= \text{Revenue}-\text{Cost} \\
> \\
> \$ &= (470+20x)(60-2x)-(60-2x)(30) \\
> \$ &= 28200-940x+1200x-40x^2-1800+60x \\
> \$ &= -40x^2+320x+26400
> \end{align}
> $$
> 
> For this, we need to have a let statement
> $$
> \text{Let }x\text{ be the number of }\$20\text{ increases in price}
> $$
> 
> Solving for $x$:
> $$
> \begin{align}
> \$ &= -40x^2+320x+26400 \\
> \$' &= -80x+320 = 0 \\
> x &= 4
> \end{align}
> $$
> 
> Solving:
> $$
> \begin{align}
> \text{Rent} &= 470+20x \\
> \text{Rent} &= 470+20(4) \\
> \text{Rent} &= \$550
> \end{align}
> $$



<pre>

</pre>
> Ex: 
> 
> A ball is thrown up in the air. Its height is given by the equation $h = -16t^2+50t$. What is its maximum height?
> 
> $$
> \begin{align}
> h' &= -32t + 50 \\ \\ \\
> 0 &= -32t + 50 \\
> t &= \frac{25}{16}s \\ \\ \\
> h &= -16(\frac{25}{16})^2 + 50(\frac{25}{16}) \\
>h &= 39.0625m
> \end{align}
> $$



<pre>

</pre>
> Ex: Box thing
> 
> By cutting away identical square from each corner of a rectangular piece of cardboard and folding up the resulting flaps, and open box can be formed. If the cardboard was $32cm$ long and $22cm$ wide find the dimensions of the box that will yield the maximum volume.
> 
> We need a let statement:
> $$
> \text{Let }x\text{ be the length of the side of the square taken out of each corner}
> $$
> 
> Equation:
> $$
> \begin{align}
> V &= x(32-2x)(22-2x) \\
> V &= 4x^3-108x^2+704x \\
> \end{align}
> $$
> 
> Solving for $x$:
> $$
> \begin{align}
> V &= 4x^3-108x^2+704x \\
> V' &= 12x^2-216x+704 = 0 \\
> x &= \frac{216\pm\sqrt{(-216)^2-4(12)(704)}}{2(12)}
> x &= ~4.27, ~13.73
> \end{align}
> $$
> 
> A value of $13.73$ is not possible so the answer for $x$ is $4.27$
> 
> Solving:
> $$
> \begin{align}
> \text{Length:} &= [32-2(4.27)] = 23.45cm \\
> \text{Length: } &= [22-2(4.27)] = 13.45cm \\
> \text{Height: } &= 4.27cm \\
> \end{align}
> $$



<pre>

</pre>
> Ex:
> 
> The base of a wooden chest is rectangular with the length being twice the width. The total volume of the chest is $12.25m^3$. The back and base are made of pine while the top, front and sides are made of oak. Oak costs 3 times as much as pine. Find dimensions of the chest to minimize costs.
> 
> $$
> \begin{align}
> 12.25 &= 2w^2h \\
> h &= \frac{12.25}{2w^2} \\ \\ \\
> l &= 2w \\ \\ \\
> c &= (top+front+ends)+(back+base) \\
> c &= 3(2w^2 + 2wh + 2wh) + 1(2wh +2w^2) \\
> c &= 8w^2 +14wh \\
> c &= 8w^2 + 85.65w^{-1} \\ \\ \\
> c' &= 16w-85.75w^{-2} \\ \\ \\
> 0 &= 16w-\frac{85.75}{w^2} \\
> w &= 1.75m \\ \\ 
> l &= 2(1.75) \\
> l &= 3.5m \\ \\ 
> h &= \frac{12.25}{2(1.75)^2} \\
> h &= 2m \\ \\ 
> \end{align}
> $$