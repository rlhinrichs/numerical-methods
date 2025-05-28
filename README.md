numerical-methods

🧮 Numerical Methods in Science & Engineering  

Dependencies:  
- numpy, scipy (all notebooks)  
- matplotlib (for visualizations in ODE/PDE notebooks)  

This collection of notebooks documents my learning process through foundational topics in numerical computing. The first half—factorization, iterative methods, and eigenvalue extraction—focuses on linear algebra as a cornerstone of modern data science. The second half—root-finding, ODEs, and PDEs—ventures into the differential equations that underlie many models in AI and scientific computing. Along the way, I investigate trade-offs in accuracy, stability, and performance as problem complexity increases.  

**Factorization Methods**: PLU, LDL, Cholesky, QR  
- Notebook: factorization.ipynb  
A walkthrough of four matrix factorization strategies—each suited to different structural properties of matrices. I explore the trade-offs in computation and discuss how matrix shape and symmetry affect method selection and result stability.  

**Iterative Methods**: Gauss-Seidel, Conjugate Gradient  
- Notebook: iterative-methods.ipynb  
Here, I compare two iterative solvers for large linear systems. The exploration shows how different configurations of the system matrix affect convergence, and highlights how iterative methods can trade computational cost for better scalability.  

**Finding Eigenvalues**: QR, SVD  
- Notebook: finding-eigenvals.ipynb  
Using QR decomposition and Singular Value Decomposition (SVD), I estimate eigenvalues and gain insight into the role of orthogonality and rank in revealing latent structure in data. This work ties closely to concepts used in machine learning and PCA.  

**Finding Roots**: Newton-Raphson  
- Notebook: finding-roots.ipynb  
A practical exploration of the Newton-Raphson method, emphasizing its strengths and limitations. I discuss the importance of good initial estimates and the sensitivity of numerical root-finding to local behavior.  

**Ordinary Differential Equations**: Boundary Value Problems  
- Notebook: ode-methods.ipynb  
Using finite difference methods, I solve boundary value problems involving second-order ODEs. This section builds on earlier insights into numerical stability and introduces discretization as a bridge between continuous theory and computational implementation.  

**Partial Differential Equations**: Elliptic, Parabolic, Hyperbolic  
- Notebook: pde-methods.ipynb  
My most challenging (and favorite!) section. I tackle PDEs using only NumPy and SciPy, implementing algorithms like Gauss-Seidel, Crank-Nicholson, and various finite difference schemes. The wave equation, in particular, was a powerful lesson in volatility and precision when simulating physical phenomena.  

**Reflection**: This project became a personal milestone in understanding how computational mathematics models the real world. It also led directly to my capstone project, which explores time-series prediction via neural networks by modeling amplitudinal shifts in data-extracted features.
👉 [Check it out](https://github.com/rlhinrichs/deepsleepai)
