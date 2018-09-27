# Orthogonal sets

A set of vectors {u1,u2,u3...up} in R^n is an orthogonal set if eac pair of distinct vectors from the set is orthogonal, that is ui.uj = 0,  for all i not equals j.

### Theorem

if S={u1,u2...up} is an orthogonal set of non zero vectors in R^n, then S is a linearly independent set.

### Orthogonal Basis

Given a subspace W of R^n, an orthogonal basis for W is a basis that is also an orthogonal set.

IF we have an orthogonal basis {u1,u2...up} for W, then given any y belongs W, we can write y in the form 
```
y = c1u1 + c2u2 +...cpup
```

### Orthogonal Projection 

Given vector u belongs R^n, the general problem is to decompose any vecto y belongs to R^n into the sum of two vectors: one that is paralel to u and one that is orthogonal t u

Specifically, we want to write y = y^ + z, where y^ = cu for some scalar c, and z is some vector orthogonal to u.

In this case {u,z} is an orthogonal basis for the plane spanned by u and y, since y^ = cu, by provious theorem
```
c = y.u / u.u
```
This gives us, called the orthogonal projection of y onto u
```
y^ = (y.u / u.u)u
```

