# Optimizaiton
This is the optimization course (lectures, labs, project) of the M2 Data Science.

**Lecturers** : Alexandre Gramfort and &amp; Robert Gower. 

This course is a review of gradient-based algorithms to solve empirical risk minimization problems both from a theorical (convergence proof and speed) and practical approach (implementation in python). In addition, it covers also the proximal approach, and deals with regularization.


**Outline** :

1. **First order algorithms**

Study & implementation of ISTA and FISTA algotithms.

2. **Coordinate descent**

A method that minimizes along coordinate directions to find the minimum of a function, making the convergence faster.

3. **Conjugate gradient descent**

Iterative method to solve linear problems with positive definite matrices.

4. **Quasi-Newton methods**

These methods leverage the Taylor expansion around the optimal to approach the hessian for approaching Newton Method (which does not scale, as such)

5. **Stochastic Gradient Descent**

The famous deep learning method that instead of calculating the gradient over the whole dataset, computes it on a mini batch. This gradient estimate has no bias but has high variance. 

6. **SGD with variance reduction**

Some extensions of gradient descent to reduce variance. Algorithms SAG, SAGA, SVRG.

# Project : Optimization strategies for anomaly detection with One class Support Vector Machines (OCSVM)


## Objectives
- Derive the dual for the one-class SVM model,

- implement a one-class SVM using a blackbox convex toolbox (cvxopt in Python),

- implement your own solvers with: Proximal gradient, Coordinate Descent, Quasi-Newton,

- present a clear benchmark of the different strategies on small and medium scale datasets.


## Authors
Benoît-Marie ROBAGLIA (benoit-marie.robaglia@polytechnique.edu)


