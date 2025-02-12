20250121104952

Tags:

## The Argument
To start, the Schrodinger equation stipulates that there DeBroglie wavelength is true and Einstein's energy-wavelength relationship are both true. Then, it must be consistent with the idea that kinetic energy and potential energy make up total energy. Finally, all of this must be linear so that the sum of two solution is itself a solution, or in other words, if $Ψ_1$ and $Ψ_{2}$ are solutions, then $ψ_{12} = Ψ_{1} + Ψ_{2}$  is a solution. Now, assuming that potentiall is constant in time ans space, then the classical expression for the forge on a particle is $\vec{F} = -\vec{\nabla}V$ so that the force on the particle would be 0. If force is 0, then the momentum and total energy are constants. The final result is $T + V = E$ or $\frac{p^{2}}{2m} = E$. 

## Consistency
To see if the Schrodinger euqation is consistent with change in time, the time derivative of the probability density has to be calculated first. $$\frac{δP}{δt} = \frac{δΨ^{*}Ψ}{δt} = Ψ^{*}\frac{δΨ}{δt} + Ψ \frac{δΨ^{*}}{δt}$$

## Solution
The infinite square well is a visualization of the energies present in a wave function. The potential within the well is 0 and anything beyond the well is infinite. This yields the wave function in the form of $$Ψ(x, t) = ψ(x)f(t)$$
which establishes the time dependency for evolution. However, the time dependency must be removed, which yields the solution to the time independent Schrodinger equation. For an independent wave, it's time independent and the form would be in $$ψ(x) = Ae^{-ikx} - Be^{ikx}$$

## Time Independent Schrodinger Equation
If potential were independent of time, then the equation can be solved with separation of variables, starting with the Schrodinger equation in the form of $$- \frac{\hbar^{2}}{2m} \frac{\partial^{2}Ψ(x, t)}{\partial x^{2}} + V(x, t)Ψ(x, t) = i\hbar \frac{\partialΨ}{\partial t}$$
Assuming that $Ψ(x, t) = ψ(x)f(t)$, then $$-f(t) \frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)f(t) = i\hbar ψ(x) \frac{\partial f(t)}{\partial t}$$
$$- \frac{1}{ψ(x)} \frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x) = i\hbar \frac{1}{f(t)} \frac{\partial f(t)}{\partial t}$$

The only way that the two sides can be equal for all $x$ and $t$ is if they're equal to a constant $E$. Solving for $i\hbar \frac{1}{f(t)} \frac{\partial f(t)}{\partial t} = E$, $\frac{df(t)}{f(t)} = -i \frac{E}{\hbar}dt$ and integrating both sides $$\ln(f(t)) - \ln(f(0)) = -i \frac{E}{\hbar}dt$$
$$\ln(f(t)) = Ce^{-i \frac{E}{\hbar}t} = Ce^{-iωt}$$
So the time independent Schrodinger equation ends up looking like $$-\frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + V(x)ψ(x) = Eψ(x)$$
$$\frac{\partial^{2}ψ(x)}{\partial x^{2}} + \frac{2m}{\hbar^{2}}(E - V)ψ(x) = 0$$
Once you set $k^{2} = \frac{2m}{\hbar^{2}}(E - V)$, the equation looks like $$\frac{\partial^{2}ψ(x)}{\partial x^{2}} + k^{2}ψ(x) = 0$$
This yields the solution $$ψ(x) = Ae^{ikx}\text{ and }Be^{-ikx}$$
and the time dependent solution $$Ψ(x, t) = Ae^{-i(kx + ωt)} + Be^{i(kx - ωt)}$$

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
1. If the slope of the wavefunction at a known point is zero or finite
2. The expected behavior of the wavefunction


