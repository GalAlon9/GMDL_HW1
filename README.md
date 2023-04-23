# GMDL_HW1
# Part 1
Part 1 of the exercise involves implementing the Ising model, which is a mathematical model used to study the behavior of ferromagnetic materials. The goal of the exercises was to simulate the model using Python and numpy and to understand how it can be used to study phase transitions.

In exercise 1, we implemented the Ising model by defining the energy function, calculating the energy of a given state, and computing the probability of transitioning to a new state.

In exercise 2, we simulated the Ising model on a small lattice to understand how the system evolves over time.

In exercise 3, we analyzed the behavior of the system as it was cooled from high temperature to low temperature.

In exercise 4, we plotted the behavior of the system as a function of temperature to visualize the phase transition.

In exercise 5, we studied the behavior of the system as it was perturbed by an external magnetic field.

In exercise 6, we implemented a Monte Carlo simulation of the Ising model to calculate the magnetization and specific heat of the system.

In exercise 7, we used a Metropolis-Hastings algorithm to sample the probability distribution of the Ising model.

In exercise 8, we used the Metropolis-Hastings algorithm to sample the probability distribution of the Ising model and calculate the expected value of certain observables.

# Part 2
## Exercise 9
The first part of the code defines two methods to estimate the expected values of two random variables in an Ising model.

The first method uses Monte Carlo simulations, running the Gibbs sampler for a fixed number of iterations and sampling from the lattice configurations generated. The method runs method1 function and prints the estimated values for two temperatures (1, 1.5, and 2).

The second method uses the same Gibbs sampler but collects data after a burn-in period. The method runs method2 function and also prints the estimated values for the same three temperatures.

## Exercise 10
The second part of the code defines a method to perform Inference by Composition of Marginals (ICM) on an Ising model with corrupted data.

The corrupted_pixel_sample function samples from the posterior distribution, which is proportional to the product of the prior and the likelihood, to obtain a sample for a pixel in the image. The ICM_pixel_sample function performs ICM by always choosing the pixel value that has the highest probability given the posterior distribution.

Finally, noise_sample generates a noise lattice used to corrupt the original Ising model.
