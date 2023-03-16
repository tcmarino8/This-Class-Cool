# Physics-188
Homework 5: Markov Chain Simulation and Hierarchical Model

Simmulated Annealing:
Traveling Salesman problem: find shortest path of many stops in a city starting and ending in same place.
Using Monte Carlo simulation with temp param that is slowly lowered from high value ->0. System shoudl equilibrate quick. Choose energy that is significantly greater than typical energy change accompanying a single monte carlo move.

cooling schedule: T = T(initial)e(-t/tau)          (tau is time constant(trial and error to find)).


Heirarchical Normal Model:
  given data that follows normal distribution
  scipy optimize to find optimal params for minus log likelihood given initial guesses(try some initials till you feel confident)
  
  
Using Gibbs Sampler:
  choosing starting points: choosing thetas(params) at random from input data(y), \mu is chosens as the mean of those initial \theta. other values can be drawn from first steps of sampler
  
finding conditional posterior distributions of all our varaibles can be gained through calculating Inv ChiSquared or Normal Distribution

Remove first 50 of sampler as it is getting adjusted

Testing for Convergence:
  Gelman Rubin statistic < 1.1
  
Run MCMC as alternative. I think this took FOREVER!!!!(insert joke about MCMC)

