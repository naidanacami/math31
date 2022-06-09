# Related Rates
(Rates of change)
***
## Displacement, Velocity, and Acceleration
***
### Average rates of change - Secant line
A secant line in this instance represents an average rate of change ($\Delta v$ and $\Delta a$). To calculate, simply apply $\frac{rise}{run}$ or $\frac{\Delta y}{\Delta x}$ to determine the average over a certain time. 
- It is the average rate of change (**slope**)
$$
\frac{\Delta y}{\Delta x}
$$
>Ex: The displacement of a particle is given by the formula $S = -\frac{2}{3}t^3 + 10t^2 -48t -5$. What is the average velocity from $t=3s$ to $t=6s$?
>$$
>\begin{align}
>S &= -\frac{2}{3}(3)^3 + 10(3)^2 - 48(3) - 5 \\
>&= -77 cm
>\end{align}
>$$
><pre></pre>
>$$
>\begin{align}
>S &= -\frac{2}{3}(6)^3 + 10(6)^2 - 48(6) - 5 \\
>&= -77 cm
>\end{align}
>$$
><pre></pre>
>$$
>\begin{align}
>V_{ave} = \frac{\Delta S}{\Delta t} = \frac{(-77) - (-77)}{6 - 3} = \frac{0}{3} = 0 cm/s
>\end{align}
>$$
>The average velocity from $t=3s$ to $t=6s$  is 0 cm/s


<pre></pre>
### Instantaneous Rate of Change - Derivative
- It is the instant rate of change
$$
\frac{\text{d}x}{\text{d}y}
$$ 
- The first derivative of a displacement/time graph is velocity
- The second derivative of a displacement/time graph is acceleration

This can be used to find:
- Velocity or acceleration at a certain point in time
- Velocity or acceleration at any point in time (first and second derivative respectively)
- At what point in time is velocity or acceleration zero (set derivatives equal to 0)
- When velocity or acceleration is positive and negative (use a sign chart)



<pre>

</pre>
## Related Rates and Geometry
***
### 2D:
#### Triangles
> Ex: Triangles with 2 moving objects
> 
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
#### Circles
> Ex: Circle area
> 
> The area of a circle is $9\pi cm^2$. The area is increasing at a rate of $\frac{\pi}{2}cm^2/min$. Find the rate of change of the radius
> 
> The equation of the area of a circle is:
> $$
> A = \pi r^2
> $$
> 
> To find the rate of change of the radius:
> $$
> \begin{align}
> A &= \pi r^2 \\
> \frac{dA}{dt} &= 2\pi r \frac{dr}{dt}
> \end{align}
> $$
> 
> To solve, we need to know $r$ when $A=9\pi$.
> $$
> \begin{align}
> A &= \pi r^2 \\
> 9\pi &= \pi r^2 \\
> \sqrt9 &= r = 3
> \end{align}
> $$
> 
> We can now solve:
> $$
> \begin{align}
> \frac{dA}{dt} &= 2\pi r \frac{dr}{dt} \\
> -\frac{\pi}{2} &= 2\pi(3)\frac{dr}{dt} \\
> \frac{dr}{dt} &= -\frac{1}{12}cm/min
> \end{align}
> $$



<pre>

</pre>
#### Rectangle:
> Ex:
> 
> The length of a rectangle is increasing at $2cm/s$ and the width is increasing at $1cm/s$. Find the rate of change of area when length is equal to $10cm$ and width is equal to $6cm$
> 
> The equation for area of a rectangle:
> $$
> A = lw
> $$
> 
> We can solve:
> $$
> \begin{align}
> A &= lw \\
> \frac{dA}{dt} &= l\frac{dw}{dt}+w\frac{dl}{dt} \\
> \frac{dA}{dt} &= (10)(1)+(6)(2) \\
> \frac{dA}{dt} &= 22cm^2/s
> \end{align}
> $$



<pre>

</pre>
### 3D
#### Sphere
> Ex: Sphere surface area
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
#### Cones
> Ex: Cone
> 
> Liquid is cleared of sediment by pouring it through a conical filter that is $16cm$ high and has a $4cm$ radius at the top. Liquid flows at $2cm^3/min$. At what rate is the depth changing when the liquid is $8cm$ deep?
> 
> Equation for volume of a cone:
> $$
> V = \frac{1}{3}\pi r^2h
> $$
> 
> There are too many variables. We can remove one by substituting an equation of similar triangles. Because we need to preserve the variable, $h$, we solve for $r$:
> $$
> \begin{align}
> \frac{r}{h} &= \frac{4}{16} \\
> r &= \frac{h}{4}
> \end{align}
> $$
> 
> We can now substitute this into the original equation:
> $$
> \begin{align}
> V &= \frac{1}{3}\pi r^2h \\
> V &= \frac{1}{3}\pi \left(\frac{h}{4}\right)^2h \\
> V &= \frac{1}{48}\pi h^3
> \end{align}
> $$
> 
> We can now solve:
> $$
> \begin{align}
> V &= \frac{1}{48}\pi h^3 \\
> \frac{dV}{dt} &= \frac{1}{16}\pi h^2\frac{dh}{dt} \\
> 2 &= \frac{1}{16}\pi 8^2\frac{dh}{dt} \\
> \frac{dh}{dt} &= -\frac{1}{2\pi}cm/min
> \end{align}
> $$

<pre></pre>
> Ex:
> 
> A water tank is built in the shape of a circular cone with a height of $5m$ and a diameter of $6m$ at the top. Water is being pumped out of the tank at a rate of $1.6m^3/min$. Find the rate at which the water level is falling when the water is $2m$ deep.
> 
> Equation of the volume of a cylinder:
> $$
> V = \frac{1}{3}\pi r^2h
> $$
> 
> There are too many variables. We can remove one by substituting an equation of similar triangles. Because we need to preserve the variable, $h$, we solve for $r$:
> $$
> \begin{align}
> \frac{r}{h} &= \frac{3}{5} \\
> r &= \frac{3}{5}h
> \end{align}
> $$
> 
> We can now substitute this into the original equation:
> $$
> \begin{align}
> V = \frac{1}{3}\pi r^2h \\
> V = \frac{1}{3}\pi \left(\frac{3}{5}h\right)^2h \\
> V = \frac{3}{25}\pi h^3 \\
> \end{align}
> $$
> 
> We can now solve:
> $$
> \begin{align}
> V &= \frac{3}{25}\pi h^3 \\
> \frac{dV}{dt} &= \frac{9}{25}\pi h^2\frac{dh}{dt} \\
> -1.6 &= \frac{9}{25}\pi 2^2\frac{dh}{dt} \\
> \frac{dV}{dt} &= \frac{9}{25}\pi h^2\frac{dh}{dt} \\
> \frac{dh}{dt} &= -\frac{10}{9\pi}m/min
> \end{align}
> $$



<pre>

</pre>
#### Cube/Rectangular Prism
> Ex: Volume
> 
> A rectangular trough is $3m$ long, $1m$ across the top and $1.3m$ deep. Water flows in at $1.6m^3m/min$. How fast is the depth rising when it is $0.5m$ deep?
> 
> Formula for volume  the volume of a rectangular prism:
> $$
> V = lwh
> $$
> 
> Since length and width are constant, we can substitute them:
> $$
> \begin{align}
> V &= lwh \\
> V &= (3)(1)h \\
> V &= 3h \\
> \end{align}
> $$
> 
> We can now solve:
> $$
> \begin{align}
> V &= 3h \\
> \frac{dV}{dt} &= 3\frac{dh}{dt} \\
> 1.6 &= 3\frac{dh}{dt} \\
> \frac{dh}{dt} &= \frac{8}{15} m/min \\
> \end{align}
> $$



<pre>

</pre>
#### Special cases
> Ex: Sphere surface area - <u>Indirectly related rates</u>
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
