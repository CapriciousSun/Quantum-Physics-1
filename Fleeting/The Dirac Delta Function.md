202502077112233

Tags:

The Dirac Delta function dictates the instantaneous shifts on the y-axis. In quantum, it's used to calculate potential. For a Hamiltonian and energy operator $$\hat{H}ψ = \hat{E}ψ$$
it can be converted to a [[The Schrödinger Equation|Schrodinger equation]] $$-\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}}ψ + λδ(x)ψ = Eψ$$
with $λ$ negative, it will have an attractive potential. Using the time independent Schrodinger equation, a system for positive and negative $x$ can be made 
#### $$\begin{cases}
ψ^{-} = Ae^{κx} \\
ψ^{+} = Βε^{-κx}
\end{cases}$$
The continuity of the wavefunction gives $ψ^{-} = ψ^{+}$ so $A = B$. The slope on the two sides is discontinuous due to the infinite $δ$ function, so the derivatives for a small $β$ are 
#### $$\begin{gather*}
\left.\frac{dψ}{dx}\right\vert_{-β} = KA \\
\left.\frac{dψ}{dx}\right\vert_{-β} = -KA
\end{gather*}$$

so $$\left.\frac{dψ}{dx}\right\vert_{β} - \left.\frac{dψ}{dx}\right\vert_{-β} = -2ΚΑ$$
Plugging into the Schrodinger equation as mentioned before 
#### $$-\int_{-β}^{β} \frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}}ψdx + \int_{-β}^{β} λδ(x)ψdx = \int_{-β}^{β} Eψdx$$
The right hand side has $β \rightarrow 0$ because the integrand is infinite, so 
#### $$\int_{-β}^{β} \frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}}ψdx = \int_{-β}^{β} λδ(x)ψdx$$
Doing the integrals separately yields an integration of 
#### $$\left.\frac{\hbar^{2}}{2m} \frac{\partial ψ}{\partial x}\right\vert_{-β}^{β}$$
