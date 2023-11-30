# bayesian_optimisation_project
Portfolio project on optimising a model for real-life data

In this capstone project, I started by manually exploring 8 functions to understand their behavior. Implementing a Bayesian optimization approach, I initially used a Gaussian Process Regressor. As the weeks progressed, I strategically modified the code, experimenting with different kernels and models, such as RBF and Matern kernels. The pivotal moment came in Week 7, scaling the successful RBF kernel to cover the entire range of 0 to 1. In later weeks, I fine-tuned parameters, broke away from local maxima, and parallelized the code for substantial computational power. The iterative process aimed to enhance the efficiency and efficacy of the optimization, yielding a more robust final solution.

## DATA
The data is composed 8 different datasets from bi-dimensional inputs to 8 dimensions inputs

## MODEL 
I choose a a Gaussian Process Regressor with a Radial Basis Function (RBF) kernel

## HYPERPARAMETER OPTIMSATION
-  RBF lengthscale
-  number_of_call
-  number of random start
