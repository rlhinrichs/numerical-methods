# numerical-methods
🧮 Numerical Methods in Science &amp; Engineering

Dependencies:
- numpy, scipy (all notebooks)
- matplotlib (ODE/PDE notebooks)

In the first three notebooks (<b>factorization.ipynb</b>, <b>iterative-methods.ipynb</b>, <b>finding-eigenvals.ipynb</b>), we walk through the historical methods of extracting meaning from data (linear algebra) and observe their cost in computational efficiency.  
In the latter three notebooks, we explore 

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

