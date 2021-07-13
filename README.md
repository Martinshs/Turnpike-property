# Turnpike Property

In this project, we will solve two optimal control problems. In particular, we will visualize the Turnpike property. We will consider an evolutive control
problem subject to a differential equation, and its stationary analogous. Both problems are solved using Gekko library.

The Notebook Turnpike Finite Dimensional.ipynb consider an optimal quadratic cost problem, in this file exemplifies the turnpike property using given matrices.

The Notebook Turnpike Finite Dimensional with Uncertainty.ipynb consider an optimal quadratic cost problem, in this file the turnpike property is exemplified when the matrices depend on a random parameter. In particular, it is analyzed when there is a random variable by multiplying the matrix. Our code addresses the case of uniform, exponential and poisson distributed random variables. Also it is possible to take one random matrix and the other not.
