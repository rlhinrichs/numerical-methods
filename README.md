# numerical-methods
🧮 Numerical Methods in Science &amp; Engineering

Dependencies:
- numpy, scipy (all notebooks)
- matplotlib (ODE/PDE notebooks)

In the first three notebooks (<b>factorization.ipynb</b>, <b>iterative-methods.ipynb</b>, <b>finding-eigenvals.ipynb</b>), we walk through the historical methods of extracting meaning from data (linear algebra)- the core algorithms of data science- and observe their cost in computational efficiency as problems become more complex. 
In the latter three notebooks (<b>finding-roots.ipynb</b>, <b>ode-methods.ipynb</b>, <b>pde-methods.ipynb</b>), we deep-dive into differential equations- the core algorithms in AI- and how to arrive at discrete solutions for complex problems.  

---  
---  

## Factorization Methods: PLU, LDL, Cholesky, QR
- factorization.ipynb

We explore four different factorization methods in linear algebra- the backbone of data processing- and observe the strengths & weaknesses of the approaches when addressing square vs rectangular matrices, and the significance of the order of operations per approach.

---  

## Iterative Methods: Gauss-Seidel, Conjugate Gradient
- iterative-methods.ipynb

We explore two principal iterative methods in solving linear algebra problems and use various problem configurations to compare & contrast the two approaches. We begin to see a trade-off in accuracy and performance.

---  

## Finding Eigenvalues: QR, SVD
- finding-eigenvals.ipynb

We explore the Gram-Shmidt Orthogonalization Process (QR Factorization) and Singular Value Decomposition (SVD) techniques in determining the λs (eigenvalues) of matrices and matrix multiplication. Here we can see how linear independence affects eigenfactorization.  

This forms the basis for extracting meaningful relationships between the data in a data set.

---  
---  

## Finding Roots: Newton-Raphson
- finding-roots.ipynb

We explore the Newton-Raphson method for finding roots of an equation. The method is robust but we have to start iterating near the solution. We're discovering the volatility of numerical solutions, and why discretizing solutions for continuous equations is difficult.

---  

## Ordinary Differential Equations: Boundary Value Problems
- ode-methods.ipynb

We explore the finite difference approximation method to solve various second-order ordinary differential equations (ODEs) whose actual continuous solutions are not computationally observable. However, since these are boundary value problems (BVPs) with parametrization, we can approximate solutions- piggybacking off our Newton-Raphson discovery earlier- which allow us to discretize a more robust approximated series of solutions for a series of data points.

---  

## Partial Differential Equations: elliptic, parabolic, hyperbolic solutions
- pde-methods.ipynb

We explore real versus approximated solutions to second-order partial differential equations (PDEs). This was definitely the most challenging (& my favorite!) project, particularly for a newbie coder like myself- we had to encode algorithms using only NumPy and SciPy (Matplotlib for visualizations) to implement the Gauss-Seidel, Crank-Nicholson, Crout Factorization methods, and the Finite Central, Forward-Difference & Backward-Difference approximation methods. The wave equation in particular (hyperbolic equation) poses the most volatility in solution-finding.

---  
---  

This is the journey that led me to my choice of capstone project exploring amplitudinal shifts as they relate to data-extracted features: seeking a purely automated solution to a complex problem that's not easy nor very efficient for our linear computational methods. [Wanna see?](https://github.com/rlhinrichs/DeepSleepAI)
