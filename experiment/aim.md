Numerical computation in Quantum Mechanics (and quantum chemistry, in particular) uses the techniques and language of Linear Algebra, by usage of vectors, matrices and various operations on them.

General Motivation: The wave function of a state of the system is typically represented by a vector ( for the coefficients) on a basis. The Operators are naturally represented as matrices over this basis. Since all properties are expectation values of the a particular operators, we see that we are required to multiply a vector with a matrix. Thus understanding matrix operations (on a vector, in particular) becomes paramount for understanding the numerical methodology of quantum mechanics.

Application of variational theorem (in the matrix formulation) would require a a solution to a set of linear equations; they are of type
, where matrix and vector
are known, and a solution for vector
has to be found. Also, the Schrodinger equation
is also naturally converted to a matrix equation on a basis set

, which is an Eigen System. Understanding the solutions for such Eigen systems are the main goal of this experiment.
