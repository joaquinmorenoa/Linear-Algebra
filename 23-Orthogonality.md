# Terminologies

### Inner Product

If u and v are the vecors in R^n we can think of these as one-coloumn matrices.

We can compute the inner product of u and v, written u.v as
```
u.v = u^Tv = u1v1 + u2v2...+unvn
```

##### Algebraic properties
  - u.v = v.u
  - (u+v).w = u.w + v.w
  - c(u.v) = (cu).v = u.(cv)
  - u.v >= 0, and u.u = 0 iif u = 0

### Length of Vector
```
||v|| = sqrt(v.v) = sqrt(v1^2 + v2^2...Vn^2)
```
### Normalizing a vector
```
||cv|| = |c|.||v||
||v/c|| = ||1/c . v || = (1/|c|).||v||
```

### Distance in R^n
```
||u-v||
```

# Orthogonality

### Orthogonal vectors

IN R^2, two vectors u and v are perpindicular if and only if distance betwen u and v is same as the distane between u and -v.
```
||u-v|| = ||u-(-v)||
||u-v||^2 = (u-v).(u-v) = u.u -2u.v + v.v
||u+v||^2 = (u-v).(u-v) = u.u +2u.v + v.v
gives, 4u.v = 0 -> u.v = 0
```

### Orthogonal component

Let W be as ubspace of R^n and let z belongs to R^n.

We say that z is othogonal to W if z is orthogonal to every vector in W.

The orthogonal component of W, written as W-perp, is the set of all vectors orthogonal to W.
```
(ColA)-perp = NulA^T
(RowA)-perp = NulA
```

