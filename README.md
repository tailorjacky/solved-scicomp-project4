Download Link: https://assignmentchef.com/product/solved-scicomp-project4
<br>
This project concerns reaction-diffusion equations and the approach can be used to model pattern formation in biology and chemical reactions. The pattern formations in biology include butterfly wing patterns, animal coat markings, fish and shell pigmentation. Pattern formation has also been observed in chemical reactions such as the chlorite-iodide-malonic acid starch reaction.

The mathematical problem is a set of nonlinear partial differential equations and they are given by

p<sub>t</sub> = D<sub>p</sub> p + p<sup>2</sup> q + C –(K+1) p                                                       (1) q<sub>t</sub> = D<sub>q</sub> q – p<sup>2</sup> q + K p                                                                 (2)

The coupled partial differential equations include the functions p(x,y,t) and q(x,y,t) and we are considering solutions on the square formed by x and y being between 0 and 40. The square is [0, 40] * [0, 40]. The Laplacian is given by The time derivatives are given by p<sub>t</sub> = dp/dt and q<sub>t</sub> = dq/dt. The positive diffusion coefficients are given by D<sub>p</sub> and D<sub>q</sub>, respectively. The two other parameters C, K are both larger than zero.

We have the following boundary conditions:

p(x,y,0) = C + 0.1 for all (x,y) belonging to the square 10 &lt; x &lt; 30 and 10 &lt; y &lt; 30. q(x,y,0) = (K/C) + 0.2   for all (x,y) belonging to the square 10 &lt; x &lt; 30 and 10 &lt; y &lt; 30.

The no-flux Neumann boundary conditions on the boundary of the square.

Neumann boundary conditions specify values of the directional derivative on the boundary where n denotes the outward unit normal vector. The flux out of the square in the direction of the unit normal vector is zero for all times on the square boundary.

The values for the different parameters could be:

D<sub>p</sub> =1 ; D<sub>q</sub> = 8 ; C=4.5 and K =9 .

You need to present contour plots of the solutions p(x,y) and q(x,y) at t=2000 for six different values of K (K= 7, 8, 9, 10, 11 and 12).


