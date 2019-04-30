## rref

The `rref` command will give you the row reduced echelon form of a matrix, meaning you will not have to do any row reduction operations yourself.

`2ND` `MATRIX` `MATH` `rref` (`B`), add in your matrix, and you'll get the row-reduced form of it.

## Eigenvalues

The formula to use when calculating eigenvalues is *det(A-\lambda I) = 0*.

Therefore, to calculate the eigenvalues on the calculator, do the following.

1. `2ND` `MATRIX` `EDIT` `[A]`. Punch in the matrix you have.
2. Now we'll plot a graph with the following function: *Y1 = det([A] - X\*idenity(n))*.
	1. to get `det`, type `2ND` `MATRIX` `MATH` `det(`
	2. To get `[A]`, type `2ND` `MATRIX` `[A]`.
	3. `X` is just the normal X variable you would use in a graph
	4. To get `identity`, type `2ND` `MATRIX`, `MATH`, `identity(`. ***n*** corresponds to the dimension of the *n\*n* matrix that `[A]` is. So if `[A]` is a 3\*3 matrix, then you type in `identity(3)`.
	5. Plot the graph and/or use the table function. 
	6. Find which *x* values gives *y = 0*. This is your eigenvalue(s).

