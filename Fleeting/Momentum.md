20250124102852

Tags:

The [[The Schrödinger Equation|Schrödinger equation]] does in fact contain information about the momentum of an object, in the form of $k = \frac{p}{\hbar}$. 

## Probability Amplitude
Since $k$ is in terms of momentum, the state function can indeed be expressed in terms of the momentum basis. 
```ad-formula
#### Momentum Probability Amplitude Formula
#### $$Φ(p) \equiv \frac{1}{\sqrt{ \hbar }}A\left( \frac{p}{\hbar} \right)$$
```

Then the [[The State Function|wavefunction]] can be expressed in the following form
```ad-formula
#### Wavefunction in Terms of Momentum Basis and Vice Versa
#### $$Ψ(x, 0) = \frac{1}{\sqrt{2π\hbar}}\int_{-\infty}^{\infty}Φ(p)e^{ipx/\hbar}dp $$
whereas the momentum probability amplitude can be expressed as
#### $$Φ(p) = \frac{1}{\sqrt{2π\hbar}}\int_{-\infty}^{\infty} Ψ(x, 0)e^{-ipx/\hbar}dx $$
```

Here, a factor of $\frac{1}{\sqrt{ \hbar }}$ is necessary for the normalization of both $Ψ$ and $Φ$.
#### Interpretations
The interpretations between the wavefunction and the probability amplitude are based on the information that they present. The wavefunction has all the information regarding the wave ready, but has trouble with extracting position as momentum is not written as a function of position. This is what the momentum probability amplitude is for, as it directly gives information regarding the probability of finding a particle with a certain momentum. They, however, both describe the same quantum state. If members of an [[Probability#Ensemble Averages|ensemble]] are in a quantum state $Ψ(x, t)$ with Fourier transform $Φ(p) = F[Ψ(x, 0)]$, then $Φ(p)dp = Φ^{\dagger}(p)Φ(p)dp$ is the probability that a momentum measurement at time $t$ will result in a particle's momentum being found between $p$ and $p + dp$. 

## Expectation Value and Uncertainty
The calculations for probability of a momentum probability amplitude uses the same procedure as a wavefunction. The expectation value when given a momentum probability amplitude is 
```ad-formula
#### Momentum Expectation Value
#### $$\langle p \rangle = \int_{-\infty}^{\infty} Φ(p)^{\dagger}pΦ(p)dp $$
```

The variances for a momentum is 
```ad-formula
#### Momentum Uncertainty
#### $$\langle p^{2} \rangle = \int_{-\infty}^{\infty} Φ(p)^{\dagger}p^{2}Φ(p)dp $$
#### $$Δp = [(p - \langle p \rangle)^{2}]^{1/2} = [\langle p^{2} \rangle - \langle p \rangle^{2}]^{1/2}$$
```

## Momentum Operator
Another way of computing the momentum from $Ψ(x, t)$ other than using the Fourier transform is expressing it in terms of an operator. 
#### The Correspondence Principle
The correspondence principle states that the behavior of a quantum system must be consistent with classical principles in the appropriate limit. The classical relation $\frac{d\langle x \rangle}{dt} = \frac{\langle p_{x} \rangle}{m}$. The operator for momentum, can therefore, be derived with this relationship.
```ad-formula
#### Momentum Operator Derivation
The initial setup involves using defining $\langle x \rangle$
#### $$\frac{d\langle x \rangle}{dt} = \frac{d}{dt}\int_{-\infty}^{\infty} xΨ^{\dagger}Ψdx = \int_{-\infty}^{\infty} x\frac{\partial Ψ^{\dagger}Ψ}{\partial t}dx $$
Using the same Schrödinger equation substitutions as the probability current, the time derivatives can be converted to spatial derivatives
#### $$\frac{d\langle x \rangle}{dt} = \int_{-\infty}^{\infty} x\frac{\partial}{\partial x} \left[ \frac{i\hbar}{2m}\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right) \right]dx = \int_{-\infty}^{\infty} \left[ \frac{i\hbar}{2m} \left(Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x}\right) \right] = -\frac{1}{m} \int_{-\infty}^{\infty} \left[ \left( Ψ^{\dagger} \frac{\hbar}{i} \frac{\partial Ψ}{\partial x} \right) \right]dx$$
From this derivation process, the final momentum operator can be found
#### $$p_{\text{op}} = \frac{\hbar}{i}\frac{\partial}{\partial x}$$
```

Using this relationship on a pure momentum state looks like
```ad-example
#### Momentum Operator of a Pure Momentum State
#### $$Ψ(x, t) = Ae^{i(px - Et)/\hbar}$$
#### $$p_{\text{op}}Ψ = \frac{\hbar}{i} \frac{\partial Ψ}{\partial x} = \frac{\hbar}{i}A \frac{ip}{\hbar}e^{i(px - Et)/\hbar} = pΨ$$
```

___
# References
[[Class 4 and 5 - Working with Wavefunctions]]
