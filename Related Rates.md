# Related Rates
(Rates of change)
***

#### Average - Secant line
- It is the average rate of change (**slope**)
$$
\frac{\Delta y}{\Delta x}
$$



<pre>
</pre>
#### Instantaneous Rate of Change - Derivative
- It is the instant rate of change
$$
\frac{\text{d}x}{\text{d}y}
$$ 




<pre>

</pre>
### Examples:
> Ex1:
> 
> A snowball is melting so the surface area decreases at a rate of $0.5\text{cm}^2/\text{min}$. Find the rate that the surface area is decreasing when the radius is $4\text{cm}$
> 
> The equation for surface area:
> $$
> SA_{sphere} = 4\pi r^2
> $$
> 
> Melting can be represented as:
> $$
> \frac{\text{d}SA}{\text{d}t} = -0.5\text{cm}^2/\text{min}\\
> $$
> 
> Solving:
> $$
> \begin{align} 
> SA &= 4\pi r^2 \\
> \frac{\text{d}SA}{\text{d}t} &= 8\pi r \frac{\text{d}r}{\text{d}t} \\
> -0.5 &= 8\pi4\frac{\text{d}r}{\text{d}t} \\
> \frac{-1}{64\pi}\text{cm}/\text{min} &= \frac{\text{d}r}{\text{d}t}
> \end{align}
> $$



<pre>

</pre>
> Ex2: Two values that aren't directly related
> 
> A spherical balloon deflates at a rate of $1\text{cm}^3/\text{min}$. Find the rate of surface area change when radius equals $4\text{cm}$. 
> 
> There is no equation that directly relates volume and surface area. We must find the rate of change of radius. 
> $$
> \begin{align}
> \frac{\text{d}V}{\text{d}t} &= -1\text{cm}^3/\text{min} \\
> \frac{\text{d}SA}{\text{d}t} &= ?
> \end{align}
> $$
> 
> The variable that links the two equations is radius. We can solve form radius:
> $$
> \begin{align}
> V &= \frac{4}{3}\pi r^3 \\
> \frac{\text{d}V}{\text{d}t} &= 4\pi r^20 \frac{\text{d}r}{\text{d}t} \\
> -1 &= 4\pi 4^2 \frac{\text{d}r}{\text{d}t} \\
> \frac{-1}{64\pi} \text{cm/min} &= \frac{\text{d}r}{\text{d}t} \\
> \end{align}
> $$
> 
> Now we have the rate of change of radius when radius is 4, we can find the rate of change of surface area:
> $$
> \begin{align}
> SA &= 4\pi r^2 \\
> \frac{\text{d}SA}{\text{d}t} &= 8\pi r \frac{\text{d}r}{\text{d}t} \\
> &= 8\pi 4 \frac{-1}{64\pi} \\
> &= -\frac{1}{2}\text{cm}^2\text{/min}
> \end{align}
> $$



<pre>

</pre>
> Ex3: Trig
> Joe is driving west at $60\text{km/h}$. Qwerty is driving south at $70\text{km/h}$. Both cars are approaching an intersection of the two roads. How fast are the two cars approaching each other when Joe is $0.4\text{km}$ away from the intersection and Qwerty is $0.3\text{km}$ away from the intersection?
> 
> We have to find the hypotenuse distance:
> $$
> \begin{align}
> c &= \sqrt{a^2+b^2} \\
> c &= \sqrt{0.4^2+0.3^2} \\
> c &= 0.5
> \end{align}
> $$
> 
> We can now solve:
> $$
> \begin{align}
> c^2 &= a^2+b^2 \\
> d^2 &= J^2+Q^2 \\
> 2d\frac{\text{d}d}{\text{d}t} &= 2J\frac{\text{d}J}{\text{d}t} + 2Q\frac{\text{d}Q}{\text{d}t} \\
> \frac{\text{d}d}{\text{d}t} &= \frac{J\cdot \frac{\text{d}J}{\text{d}t}+ Q\cdot \frac{\text{d}Q}{\text{d}t}}{c} \\
> \frac{\text{d}d}{\text{d}t} &= \frac{60\cdot 0.4 + 70\cdot 0.3}{0.5} \\
> \frac{\text{d}d}{\text{d}t} &= -90\text{km/h}
> \end{align}
> $$



<pre>

</pre>
Ex4: yeah 