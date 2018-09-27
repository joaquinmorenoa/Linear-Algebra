# Determinants

Determinant of 2x2matrix
```
det{{a,b},{c,d}} = ad-bc
```
Similarly, determinant of 3x3 matrix:
```
de{{a,b,c},{d,e,f},{g,h,i}} = aei + bfg + cdh - ceg - bdi - afh
```
### Breaking down determinants

In order to breakdown the determinant formula. we must first define a cofactor

Given a squae nxn matrix A, the minor M(i,j) is the determinant of the matrix obtained by eliminating row i and coloumn j from A.

##### Cofactor

The cofacor C(i,j) is deined to be the minor M(i,j) multiplied by +-1
```
Specifically, C(i,j)  = M(i,j)*(-1)^(i+j)
```

### To compute determinant

  - Choose any two row or coloumn of the matrix.
  - Multiply each entry of the chosen row/colounm by the corresponding cofactor.
  - Add up the result

### Properties of Determinants
   - The square matrix A is invertible if and only if detA not equals 0.
   - Given a square matrix A, we have detA = detA^T
   - given a square matrix A and B of the same size detAB = detA . detB
