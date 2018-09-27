# Eigenvectors and Eigenvalues

Given an nxn matrix A, a non zero vector x is an eigenvector of A if Ax = cx for some scalar c.

A scalar c is an eigenvalue of A if there exists a nontrivial solution of Ax = cx. Such a solution is called an eigenvector corresponding to c.
```
A^kx = c^kx
```

### Eigenspaces

For a given values of scalar c, the set of all solutions to (A - cI)x = 0 is just the null space of the matrix A-cI

So the set fo all vectors x with Ax = cx is a subspcae of R^n.

The eigenspace of A corresponding to c is the set of all eigenvectors of A corresponding to c, together with the zero vector.

### Eigenvalues of the Triangular Matrices 

Theorem: The eigen values of a triangluar matrix are the diagonals entries of the matrix.

### Eigenvectors for distinct Eigenvalues

Theorem: If v1,v2...vr are the eigenvectors of a matrix A that corresponds the distinct eigenvalues c1,c2,c3,,,cr then the set {v1,v2,v3,..vr} is a linearly dependent set.
