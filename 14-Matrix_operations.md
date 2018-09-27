# Properties of Matrix Opertions

### Basic properties
Let A, B and C be m x n matrices
  - A + B  =  B + A    [commutative]
  - A + (B + C)  =  (A + B) + C    [associative]

There is a unique m x n matrix O with
  - A + O  =  A        [additive identity]

For any  m x n matrix A there is an m x n matrix B (called -A) with
  - A + B  =  O        [additive inverse]

### Matrix Multiplication
If C=AB

![mm](https://wikimedia.org/api/rest_v1/media/math/render/svg/3cfeccef1c8c7e6da0ddf08daed8dbf3c6f50c5e)

In general, AB is not equal to BA.

If AB = AC, then it is nottrue in general that B = C.

If AB = 0 then we cannot concule that A=0 or B=0.

### Powers of Matrix

Given a square matrix A and a positive integer k, we define A^k to be the product of k  copies of A.
```
A^k = A*A*A*...k times
```
By definiton, A^0 = Identity matrix

### Transpose of Matrix

Given a matrix A, the transpose of A, written as A^T, is the matrix whose colomns are formed from the rows of A.

##### Properties of Transpose

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/53958fe7d09200196dfa76e95afb16218e7cfa52)

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/2c9dd2da092b4fc399604b16ee6d65cbbec8faae)

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/6b2a9e0486ff6df1cc4087b25968ec34b76afb37)

![](https://wikimedia.org/api/rest_v1/media/math/render/svg/37762cd33e79f4eb915d4c07747c2163254a8ef6)

### Inverse of Matrix

Given a square matrix A, th multiplicative inverse of A is amtrix A^-1 such that 
```
A.A^-1 = A^-1.A = I
```
Not Every matrix has an inverse.

A matrix that does not have an inverse is called singular.

A matrix that does have an ivverse is called invertible or nonsingluar.

##### Theorem 
If A = {{a,b},{c,d}} and ad-bcdoesnt equal zero, then A is invertible and
```
A^1 = 1/ad-bc * {{d,-b},{-c,a}}
```

