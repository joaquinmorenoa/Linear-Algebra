# Singular Value Decomosition

For any mxn matric A, it is possible to create a decomposition A = (Q)(D)(P^-1)

For any matrix Am the matric (A^T)(A) is symmetric and so (A^T)(A) is orthogonally diagonalizible.

### The singular values of a matrix

The eigenvalues of (A^T)(A) are nonnegative.

By renumbering the eigenvalues i decreasing order: 
```
c1 >= c2 >= c3 ...>= cn >= 0
```

The singular values of A are the numbers mu = sqrt(ci), where mu = length of vector Avi.

### Theorem

Suppose M is a m × n matrix whose entries come from the field K, which is either the field of real numbers or the field of complex numbers. Then there exists a factorization, called a 'singular value decomposition' of M, of the form 

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/3315de0d8549ccefd4c619e4e6cce6ba041dde3c)

    U is an m × m unitary matrix over K (if K = R  , unitary matrices are orthogonal matrices),
    Σ is a diagonal m × n matrix with non-negative real numbers on the diagonal,
    V is an n × n unitary matrix over K, and V∗ is the conjugate transpose of V.
