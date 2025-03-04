
# Eigenvalues and Eigenvectors

## What are Eigenvalues and Eigenvectors?

Consider a matrix **A** and a vector **x**, such that:

\[ b = Ax \]

The resulting vector **b** is the result of applying some transformation (like rotation, scaling, etc.) to the original vector **x** by the matrix **A**.

### Eigenvectors and Scaling

However, for **Eigenvectors**, the transformation is always just scaling. For example:

If **x** is an Eigenvector, then the resulting vector **b** from **b = Ax** will just be a stretched or squeezed version of **x**, and no rotation will occur.

The equation for an Eigenvector and its corresponding Eigenvalue is:

\[ Ax = \lambda x \]

Where:
- **A** is the matrix.
- **x** is the Eigenvector.
- **\lambda** is the Eigenvalue.

In this equation, **Ax** is just a scalar multiple of **x**, where **\lambda** is that scalar. Therefore, **\lambda** represents how much the vector **x** is scaled (stretched or compressed).

### Conclusion

In general, the **Eigenvalue** represents the factor by which a vector is scaled. The **Eigenvector** is the vector that can only be scaled, without undergoing any rotation or other transformation.
