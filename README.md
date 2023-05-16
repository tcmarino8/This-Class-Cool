# Physics-188
My work from physics 188
MLE, MCMC, Distributional Approximation, Expectation Maximization (EM)

In this homework assignment we tackle new ways to expand on predictive models for both quasar spectra and supernova.

Supernova data allows us to confirm that dark energy exists by the accelarating expansion of the universe. This is done by looking at redshifting (the process of light taking longer to reach us than it should due to expansion). 
  Calculating the likelihood using maximum likelihood estimation(MLE), using scipy optimize for an equation and initial params, then using Metropolis algorithm with "EMCEE"(Ensemble Sampler methods). Use Gelman Rubin Stat to check for convergence. You want the value to be less than 1.1.

Look at content below "Reference: See pg. 8-16 " for the Expectation-Maximization algorithm. Then you can reconstruct your data quite well, we only needed 3 Principle components. After each component is gathered you must subtract the projection from the data matrix. 
  Best way to get big picture trends(smooth) and ignore all the sharp characteristics.
  weighting by the inverse variance allows you to ensure noisy observations don't sway solutions.

Then in problem 2(Quasar Spectra) we do a simliar process but for PCA, so using matricies!!!
Friedmann equation, luminosity distance, Big Bang cosmology,
