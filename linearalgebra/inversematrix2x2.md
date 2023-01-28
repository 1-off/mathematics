The inverse of a 2x2 matrix A is given by the formula
```
A^-1 = 1/det(A) * [ d, -b],
[-c, a]

Where det(A) = ad - bc is the determinant of A and a, b, c, and d are the elements of A.

In this case,
A = [[1,2],
[3,4]]

det(A) = (14) - (23) = -2

A^-1 = 1/-2 * [[4,-2],
[-3,1]]

So the inverse matrix of [1,2,3,4] is [[4,-2],
[-3,1]]
```
However, it is important to note that a matrix only has an inverse if its determinant is non-zero. In this case, the determinant is -2, which is not zero, so the matrix does have an inverse.
