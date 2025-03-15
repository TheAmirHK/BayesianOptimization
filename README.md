# Bayesian Optimization
Bayesian Optimization (BO) is a probabilistic model-based optimization technique used to find the global minimum or maximum of expensive-to-evaluate functions.
Bayesian Optimization is rooted in Bayesian inference, which originates from Bayes’ Theorem. While Thomas Bayes initially formulated the theorem, Pierre-Simon Laplace extended and formalized it, laying the groundwork for modern Bayesian statistics.

Laplace was instrumental in developing probabilistic reasoning and Gaussian distributions, which are now fundamental to Bayesian Optimization. The use of Gaussian Processes (GPs) in BO also has historical connections to Laplace’s work on least squares and probability distributions.
But, what's Bayes' theorem ? Bayes’ Theorem describes how to update probabilities based on new evidenceThe mathematical formula is:

$P(A|B) = \frac{P(B|A) P(A)}{P(B)}$

where:

- **$P(A|B)$** is the **posterior probability** (the probability of $A$ given that $B$ has occurred).
- **$P(B|A)$** is the **likelihood** (the probability of $B$ occurring given that $A$ is true).
- **$P(A)$** is the **prior probability** (our initial belief about $A$ before seeing $B$).
- **$P(B)$** is the **marginal probability** (the total probability of $B$ occurring across all possible values of $A$).
