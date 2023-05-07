Download Link: https://assignmentchef.com/product/solved-m232-homework-5-poisson-problem
<br>
The Matlab script poisson.m solves the Poisson problem on a square <em>m </em>× <em>m </em>grid with ∆<em>x </em>= ∆<em>y </em>= <em>h</em>, using the 5-point Laplacian. It is set up to solve a test problem for which the exact solution is <em>u</em>(<em>x,y</em>) = exp(<em>x </em>+ <em>y/</em>2), using Dirichlet boundary conditions and the right hand side <em>f</em>(<em>x,y</em>) = 1<em>.</em>25exp(<em>x </em>+ <em>y/</em>2).




<ul>

 <li>Test this script by performing a grid refinement study to verify that it is second orderaccurate. Plot the error versus mesh width and compute an estimate for the convergence rate.</li>

 <li>Modify the script so that it works on a rectangular domain [<em>a<sub>x</sub>,b<sub>x</sub></em>] × [<em>a<sub>y</sub>,b<sub>y</sub></em>], but still with ∆<em>x </em>= ∆<em>y </em>= <em>h</em>. Verify that your computed solution agrees with the exact solution.</li>

 <li>Further modify the code to allow ∆<em>x </em>6= ∆<em>y </em>and test the modified script. Verify that your computed solution agrees with the exact solution.</li>

 <li>When ∆<em>x </em>6= ∆<em>y</em>, how do you expect the error to behave? Give a brief discussion on your reasoning.</li>

</ul>

1