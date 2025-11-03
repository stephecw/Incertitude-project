# 🎯 Bayesian Inference for Inverse Problems — Incertitude Project

This project addresses a **Bayesian approach to solve an inverse problem**: estimating hidden physical parameters of a nonlinear model from noisy observations.

Using **Markov Chain Monte Carlo (MCMC)** and **Bayesian inference**, the project allows uncertainty quantification and robust parameter estimation in physics-inspired models.

---

## ✅ Objectives

- Estimate unknown physical parameters from noisy measurements  
- Use **Bayesian inference** to obtain a distribution of parameters (not just point estimates)  
- Quantify **uncertainty, credibility intervals and posterior distributions**  
- Apply MCMC (Metropolis–Hastings) to sample from the posterior distribution  

---

## ⚙️ Workflow

1. **Model Definition**  
   - Define a physical model \( f(x, \theta) \) with parameters \( \theta \) (e.g., viscosity, diffusion).

2. **Synthetic Data Generation**  
   - Simulate noisy observations to emulate real-world measurements.

3. **Likelihood Formulation**  
   - Define the likelihood function + Gaussian/log-likelihood approximation.

4. **Bayesian Inference & MCMC**  
   - Use **Metropolis–Hastings algorithm** to sample from the parameter posterior.

5. **Posterior Analysis**  
   - Analyze:
     - Convergence of chains  
     - Acceptance rates  
     - Posterior distributions  
     - Confidence / credible intervals  



