20250114113015

Tags: [[Mathematics]]

The probability of a specific outcome over the total number of experiments it the normal probability, represented as $$P(a) = \frac{n_{a}}{N}$$

## Normalized Probability
A normalized probability is where the total result of measurement ends up being 1. The probability of a specific outcome happening is the number of times something occurs over the total number of times something happen. The probability of a set of outcomes is $$P(a \text{ or } b \text{ or }\dots) = \sum_{j = a}^{c}P(j) = \frac{1}{N}\sum_{j = a}^{c}n_{j}$$
A normalized probability will have a total probability of $$\sum_{j = a}P(j) = 1$$

## Ensemble Averages
The probability of an event result is defined by the fraction of times that the result occurs for a large number of identical systems. The collection of such a system is called the ensemble.
#### Expectation Values
The expectation value of a system is the average probability that an outcome occurs. The expectation value of an ensemble is found through the sum 
```ad-formula
#### Expectation Value Formula
#### $$\langle q \rangle = \overline{q} = \frac{\sum_{j = 1}^{M}q_{j}P(q_{j})}{\sum_{j = 1}^{M}P(q_{j})}$$
```

#### Uncertainty
Another statistic to keep in mind is the uncertainty, which is the dispersion within the probability distribution. It is found with the formula
```ad-formula
#### Variance Formula
#### $$σ_{q} = \langle (q - \langle q \rangle)^{2} \rangle$$
```

## Continuous Probability
For a wave, the probability is continuous, needing integration as opposed to summations. Measurement is typically done over the an infinitesimal range as $P(x)dx$, where $P(x)$ is the probability density. Given the probability density, the expectation value can be computed. 
```ad-formula
#### Continuous Expectation Value Formula
#### $$\langle x \rangle = \int_{-\infty}^{\infty} xP(x)dx$$
#### $$\langle q(x) \rangle = \int_{-\infty}^{\infty} q(x)P(x)dx$$
```

___
# References
[[Class 2 - Complex numbers – Exponential representation Wave Superposition]]
