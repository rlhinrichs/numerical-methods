# numerical-methods
🧮 Numerical Methods in Science &amp; Engineering

Dependencies:
- numpy, scipy

--  

## Factorization Methods: PLU, LDL, Cholesky, QR
- factorization.ipynb

In this discussion, we use various decomposition methods to demonstrate that Linear Algebra is Associative but not Commutative due to the order of operations being a function of transforming the basis vectors over linearly separable columns (dimensions). For this reason, the dimensional behavior of $A^{T}\\times A$ resembles $A^{-1}\\times A$, which is the identity matrix. When solving $Ax = b$, we're tasked with finding which vector $x$ can take $b$ from its transformed state back to its original pre-transformed state, where $x$ describes the $(\\hat{i},\\hat{j},\\hat{k})$ coordinate of a 3D system (for example; we can actually use any number of dimensions). However, the number of dimensions must be linearly separable, which we've proven here. We've demonstrated what happens, no matter which choice of factorization method used to decompose $A\\times A^{T}$- the opposite order of operations to the permutation matrix- that successful decomposition is impossible if the number of rows exceeds the number of columns in $A$. The rank of $A$ must equal the number of dimensions in the column space of $b$ in order for a solution $x$ to exist.

--  

