20250114114615

Tags: 

The state function $Ψ$ is the realizable state a system will be in. All accessible information regarding a system is represented by the state function. The wave function is used to denote the state function at a certain time and position as $Ψ(x, t)$. 

## Born's Postulate
Born's postulate states that a measurement to locate a particle associated with a certain wave function $Ψ(\vec{r}, t)$ will result in a probability $P(\vec{r}, t)$ that the particle will be found in the volume $dv$ around the position $\vec{r}$ and it is equal to $P(\vec{r}, t)dv = Ψ^{*}(\vec{r}, t)Ψ(\vec{r}, t)dv$. 

## Superposition
The principle of superposition states that if $Ψ_{1}$ and $Ψ_{2}$ represent two physically realizable states of a system, then the linear combination $Ψ = c_{1}Ψ_{1} + c_{2}Ψ_{2}$ is also a physically realizable state of the system. 

## Normalization
When doing operations on a wave function, it must be normalized first. In order to obtain the [[Probability#Normalized Probability|normalized probability]] of a state function, a constant $M$ needs to be obtained.
```ad-formula
#### Normalization Formula
#### $$M = \int_{-\infty}^{\infty} Ψ^{'} * (\vec{r}, t)Ψ^{'}(\vec{r}, t)dv$$
Then, the wave function will be multiplied by $\frac{1}{\sqrt{M}}$
#### $$Ψ(x, t) = \frac{Ψ^{'}(x, t)}{\sqrt{M}}$$
```

## Physical Constraints
There are a few rules that a physical wavefunction would have. 
1. A physical wavefunction must be normalizable
2. A physical wavefunction must be single valued
3. A physical wavefunction and its spatial derivatives must be continuous and smooth

## Expectation Value
The [[Probability#Expectation Values|expectation value]] of a wavefunction is calculated in the same way as continuous probability, just with different notation. For an observable $Q$, the expectation value is calculated as 
```ad-formula
#### Expectation Value for a Wavefunction
#### $$\langle Q \rangle = \frac{\int_{-\infty}^{\infty} Ψ^{\dagger}QΨdv}{\int_{-\infty}^{\infty} Ψ^{\dagger}Ψdv}$$
```

## Uncertainty
The [[Probability#Uncertainty|uncertainty]] of a wavefunction with the observable $Q$ is calculated as
```ad-formula
#### Uncertainty for a Wavefunction
#### $$ΔQ = [\langle (Q - \langle Q \rangle)^{2}]^{\frac{1}{2}} = [\langle Q^{2} \rangle - \langle Q \rangle^{2}]^{\frac{1}{2}} $$
```

## Free Space Solution
For a $V(x) = 0$, there are some requirements for the wavefunction to be solvable.
1. If $Ψ$ is normalizable, it must go to zero as the integration is over infinity
2. $Ψ$ must be complex, since the [[The Schrödinger Equation|Schrodinger equation]] has a $i$ on the right hand side that must be accounted for
3. $Ψ$ must not violate the homogeneity of free space, meaning that the probability must remain the same even after translating $Ψ$ to be integrated over an arbitrary, non-infinitesimal distance

## Conservation of Probability
[[Probability]] must be conserved over time, meaning that the probability of finding the particle should not change as time evolves. An example of finding conservation would be with the [[The Schrödinger Equation|Schrödinger equation]]. 
```ad-example
#### Conservation of Probability in the Schrödinger Equation
For starters, the time derivative of the probability density should be calculated
#### $$\frac{\partial P}{\partial t} = \frac{\partial Ψ^{\dagger}Ψ}{\partial t} = Ψ^{\dagger}\frac{\partial Ψ}{\partial t} + Ψ\frac{\partial Ψ^{\dagger}}{\partial t}$$
Then the Schrödinger equation will be evaluated using the time derivative
#### $$\begin{cases}\frac{\partial Ψ}{\partial t} = \frac{1}{i\hbar}\left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ}{\partial x^{2}} + V(x)Ψ \right) \\ \frac{\partial Ψ^{\dagger}}{\partial t} = -\frac{1}{i\hbar}\left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2} Ψ^{\dagger}}{\partial x^{2}} + V(x)Ψ^{\dagger} \right) \end{cases}$$
The space derivatives of the Schrödinger equation will replace the time derivatives
#### $$\begin{gather*}\frac{\partial P}{\partial t} = Ψ^{\dagger} \frac{1}{i\hbar}\left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ}{\partial x^{2}} + V(x)Ψ \right) - Ψ\frac{1}{i\hbar}\left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ^{\dagger}}{\partial x^{2}} + V(x)Ψ^{\dagger} \right) = \frac{i\hbar}{2m}\left( Ψ^{\dagger}\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ}{\partial x^{2}} - Ψ\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ^{\dagger}}{\partial x^{2}} \right) \\ = \frac{i\hbar}{2m} \frac{\partial}{\partial x}\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right)\end{gather*}$$
From this, the rate of change of total probability can be derived 
#### $$\frac{\partial}{\partial t} \int Pdx = \int \frac{\partial P}{\partial t}dx = \frac{i\hbar}{2m} \int_{-\infty}^{\infty} \frac{\partial}{\partial x}\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right)dx = \frac{i\hbar}{2m}\left.\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right)\right\vert_{-\infty}^{\infty} = 0$$
This shows that if a wavefunction is a solution the the Schrödinger equation and is normalizable, then the probability must be conserved
```

## Probability Current
The derivations for probability conservation also yields the probability current, which is useful for thinking about traveling particles. 
```ad-formula
#### Probability Current Density Formula
#### $$-\frac{i\hbar}{2m}\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right) \equiv j_{x}(x)$$
```

An example of where this can be used is in a pure momentum current. 
```ad-example
#### Probability Current Density for a Pure Momentum Current
#### $$Ψ_{p0}(x, t) = Ae^{\frac{i(p_{0}x - Et)}{\hbar}} $$
#### $$j_{x}(x) = -\frac{i\hbar}{2m}\left( Ψ^{\dagger}\frac{\partial Ψ}{\partial x} - Ψ\frac{\partial Ψ^{\dagger}}{\partial x} \right) = -\frac{i\hbar}{2m}\left( \frac{A^{\dagger}Aip_{0}}{\hbar} - \left( -\frac{A^{\dagger}Aip_{0}}{\hbar} \right) \right) = \frac{|A|^{2}p_{0}}{m} = |A|^{2}v_{0} $$
```

## The Gaussian Wavepacket
The wavefunction can normally be simplified by calculating for $t = 0$ by a normal Gaussian function centered at some $x_{0}$ and moving with an average wavenumber $k_{0}$ 
```ad-formula
#### Gaussian Wavepacket Formula
#### $$Ψ(x, 0) = \left( \frac{1}{σ_{x}\sqrt{ 2π }}^{1/2}e^{ik_{0}x}e^{-\frac{(x - x_{0})^{2}}{4σ_{x}^{2}}} \right)$$
```
From here, the coefficient can be solved for with
```ad-formula
#### Gaussian Coefficient Formula
#### $$A(k) = \frac{1}{\sqrt{ 2π }} \left( \frac{1}{σ_{x}\sqrt{ 2π }} \right)^{1/2}\int_{-\infty}^{\infty} e^{i(k_{0} - k)x}e^{-\frac{(x - x_{0})^{2}}{4σ_{x}^{2}}} \, dx  $$
```

## Time Evolution
If the general form of a wavefunction is as follows 
```ad-formula
#### General Form of a Wavefunction in Terms of Gaussian Coefficient and Vice Versa
#### $$Ψ(x, t) = \frac{1}{\sqrt{ 2π  }}\int_{-\infty}^{\infty} A(k)e^{-i(kx - ωt)} \, dk $$
then if you're given $Ψ(x, 0)$ you can figured out $Ψ(x, t)$
#### $$A(k) = \frac{1}{\sqrt{ 2π }}\int_{-\infty}^{\infty} Ψ(x, 0)e^{-i(kx)} \, dx $$
```

## Group Velocity


___
# References
[[Class 2 - Complex numbers – Exponential representation Wave Superposition]]
[[Class 4 and 5 - Working with Wavefunctions]]
