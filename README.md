# Incertitude-project

This project tackles a Bayesian resolution of an inverse problem. The goal is to estimate hidden physical parameters of a nonlinear model using noisy observations.

Main steps include:\
	•	Defining a physical model f(x) depending on parameters (e.g., viscosity, diffusion constants).\
	•	Generating synthetic noisy observations to simulate measurement data.\
	•	Building the likelihood function and its Gaussian/log-likelihood approximation.\
	•	Implementing a Metropolis–Hastings MCMC algorithm to sample from the posterior distribution of the parameters.\
	•	Analyzing convergence, acceptance ratios, posterior distributions, and confidence intervals.

This workflow provides a complete Bayesian framework for parameter estimation, uncertainty quantification, and model validation in physics-inspired systems.
