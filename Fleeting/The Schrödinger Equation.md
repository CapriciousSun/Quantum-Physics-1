20250121104952

Tags:

## The Argument
There are a few points for an argument for the plausibility of the Schrödinger equation. 
1. The Schrödinger equation is consistent with the postulates of  DeBroglie wavelength and Einstein's energy-wavelength relationship
2. The Schrödinger equation is consistent with the idea that kinetic energy and potential energy make up total energy
3. The Schrödinger equation is linear so that the sum of two solution is itself a solution
	- Or in other words, if $Ψ_1$ and $Ψ_{2}$ are solutions, then $ψ_{12} = Ψ_{1} + Ψ_{2}$  is a solution.
Now, assuming that potential is constant in time and space, where $V(x, t) = V_{0} = V$. Then the classical expression for the force on a particle is $\vec{F} = -\vec{\nabla}V$ so that the force on the particle would be 0. If force is 0, then the momentum and total energy are constants. The final result is $T + V = E$ or $\frac{p^{2}}{2m} = E$. Using the Einstein and de Broglie postulates, the following is true.
```ad-formula
#### Energy in Terms of Wavelength
#### $$-\frac{\hbar^{2}}{2mλ^{2}} = hf \text{ or } \frac{\hbar^{2}k^{2}}{2m} = \hbar ω$$
```

Considering a traveling wave with the representation $Ψ = f(kx - ωt) = f(u)$, the wavefunction must be derived to maintain linearity.
```ad-formula
#### Derivation Process for a Wavefunction
#### $$\frac{\partial Ψ}{\partial x} = \frac{\partial Ψ}{\partial u} \frac{\partial u}{\partial x} = k\frac{\partial Ψ}{\partial u}$$
#### $$\frac{\partial^{2} Ψ}{\partial x^{2}} = k^{2}\frac{\partial^{2} Ψ}{\partial u^{2}}$$
#### $$\frac{\partial Ψ}{\partial t} = -ω\frac{\partial Ψ}{\partial u} $$
It can be concluded that the second derivative of position provides a coefficient of $k^{2}$ whereas the first derivative of time provides a coefficient of $-ω$. So Schrödinger proposed the following wave relations.
#### $$α\frac{\partial^{2}Ψ}{\partial x^{2}} = β\frac{\partial Ψ}{\partial t}$$
```

Using these identities, the wavefunction just needed coefficients that work for the relations mentioned.
```ad-formula
#### The Schrödinger Equation
#### $$-\frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ(x, t)}{\partial x^{2}} + V(x, t)Ψ(x, t) = i\frac{\partial Ψ}{\partial t}$$
```

## Consistency
To see if the Schrodinger euqation is consistent with change in time, the time derivative of the probability density has to be calculated first. $$\frac{δP}{δt} = \frac{δΨ^{*}Ψ}{δt} = Ψ^{*}\frac{δΨ}{δt} + Ψ \frac{δΨ^{*}}{δt}$$

## Solution
The infinite square well is a visualization of the energies present in a wave function. The potential within the well is 0 and anything beyond the well is infinite. This yields the wave function in the form of $$Ψ(x, t) = ψ(x)f(t)$$
which establishes the time dependency for evolution. However, the time dependency must be removed, which yields the solution to the time independent Schrodinger equation. For an independent wave, it's time independent and the form would be in $$ψ(x) = Ae^{-ikx} - Be^{ikx}$$

## Time Independent Schrodinger Equation
If potential were independent of time, then the equation can be solved with separation of variables. 
```ad-formula
#### Solving for the Schrödinger equation
Assuming that $Ψ(x, t) = ψ(x)f(t)$, then 
#### $$\begin{gather*}-f(t) \frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)ψ(x)f(t) = i\hbar ψ(x) \frac{\partial f(t)}{\partial t} \\ - \frac{1}{ψ(x)} \frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)ψ(x) = i\hbar \frac{1}{f(t)} \frac{\partial f(t)}{\partial t}\end{gather*}$$
With this, the only way for the two sides to be equal is to make them equal to a constant $E$
#### $$- \frac{1}{ψ(x)} \frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)ψ(x) = i\hbar \frac{1}{f(t)} \frac{\partial f(t)}{\partial t} = E$$
Solving for the right hand side $i\hbar \frac{1}{f(t)} \frac{\partial f(t)}{\partial t} = E$, $\frac{df(t)}{f(t)} = -i \frac{E}{\hbar}dt$ and integrating both sides 
#### $$\ln(f(t)) - \ln(f(0)) = -i \frac{E}{\hbar}dt$$
#### $$f(t) = Ce^{-i \frac{E}{\hbar}t} = Ce^{-iωt}$$
Solving for the right hand side is 
#### $$-\frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)ψ(x) = Eψ(x)$$
which is the time-independent Schrödinger equation. Another form of this equation is like 
#### $$\frac{\partial^{2}ψ(x)}{\partial x^{2}} + \frac{2m}{\hbar^{2}}(E - V)ψ(x) = 0$$
```

Isolating the time independent form is useful for traveling waves
```ad-formula
#### Solving for Time-Independent Schrödinger Equation
Set $k^{2}$ to $\frac{2m}{\hbar^{2}}(E - V)$ and substitute
#### $$ψ(x) = Ae^{ikx} + Be^{ikx} \text{ or } A'\sin(kx) + B'\cos(kx)$$
So the overall solution including time dependence is
#### $$Ψ(x, t) = Ae^{-i(kx + ωt)} + Be^{i(kx - ωt)}$$
```

## Hamiltonian
The Hamiltonian $$\hat{H}ψ = Εψ$$
which is an energy eigenstate/eigenvalue. 

## Energy
The energy of a time-independent Schrodinger equation is $E > V_{0}$, and the implications of that is
#### $$\underbrace{e^{ikx}}_{\sin(kx)} : \underbrace{e^{-ikx}}_{\cos(kx)}$$

## Numerical Solutions
Let $\hbar = m = 1$ in the TISE, so 
#### $$\frac{\partial^{2}ψ(z)}{\partial(z)^{2}} = -2[E - V(z)]ψ$$
Then, the time independent Schrodinger equation is convereted to a finite differential equation 
#### $$\begin{gather*}
z \implies z_{j} = jΔz \\
ψ(z) \implies ψ(z_{j}) \equiv ψ_{j} \\
V(z) \implies V(z_{j}) \equiv W_{j}
\end{gather*}$$
So, the Schrodinger equation can be converted to
#### $$\begin{gather*}
ψ_{j + \frac{1}{2}}^{'} \equiv \frac{ψ_{j + 1} - ψ_{j}}{Δz} \\
ψ_{j}^{''} = \frac{ψ_{j + \frac{1}{2}}^{'} - ψ_{j - \frac{1}{2}}^{'}}{Δz} = \frac{ψ_{j + 1} - 2ψ_{j} + ψ_{j - 1}}{Δz^{2}} \\
ψ_{j + 1} = 2ψ_{j} - ψ_{j - 1} + 2Δx^{2}[V_{i} - E]ψ_{ι}
\end{gather*}$$
Then, the information need to continue are 
4. If the slope of the wavefunction at a known point is zero or finite
5. The expected behavior of the wavefunction


