# Optimization for Data Science Course @ Télécom ParisTech by Alexandre Gramfort & Stéphane Gaïffas
This course covers a general review of theory and practise of gradient-based algorithms to solve empirical risk minimization problems (mainly linear regression, logistic regression and support vector machines). For all methods, it covers also the proximal approach, dealing with regularization.

## Labs and project submitted for Optimization Course

### Labs
4 labs that cover the following:
- First order algorithms: Study & implementation of ISTA and FISTA algotithms: the first is a vanilla gradient descent algorithm, the second is its accelerated version
- Coordinate descent
- Conjugate gradient descent
- Quasi-Newton methods
- Stochastic Gradient Descent

### Project
The project covers the following:

- Derive the duals for SVMs with and without intercept
- Implement an SVM using a blackbox convex toolbox (cvxopt in Python)
- Implement your own solvers for the without intercept case: Proximal gradient, Coordinate Descent, Newton, Quasi-Newton
- Present a clear benchmark of the different strategies on small and medium scale datasets
