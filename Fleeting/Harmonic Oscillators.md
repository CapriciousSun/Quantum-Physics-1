20250311102338

Tags:

A harmonic oscillator is classically used to describe springs, but here, the function for spring potential energy is used for approximating the vibration of molecules.

## Formalism
The formula used here is 
#### $$V(x) = \frac{1}{2}kx^{2}$$
where it forms a parabola with some constraint in the form of an energy level. With the analogy of the spring, the function is rewritten in terms of oscillation frequency as 
#### $$V(x) = \frac{1}{2}kx^2 = \frac{1}{2}mω^{2}x^{2};\ ω = \sqrt{ \frac{k}{m} }$$
So the Schodinger equation can be evaluated to
#### $$-\frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ}{\partial x^{2}} + \frac{1}{2}mω^{2}x^{2}ψ = Eψ$$
The approximate solution for a large $x$ value
#### $$e^{-(mω/\hbar)x^{2}}$$
This means the wavefunction will be proportional to the Hermite polynomial with the factored out $x$ value
#### $$ψ(x) \propto H_{n}(x)e^{-(mω_{n}/\hbar)x^{2}};\ \ \hbar ω_{n} = \left( n + \frac{1}{2} \right) \hbar ω_{0}$$

The behavior of the solution, due to its size, will be factoring out the behavior of the solution. So
#### $$\text{assume } y = \sqrt{ \frac{mω}{\hbar}x }\ \&\ ε = \frac{2E}{\hbarω} $$
The change in the spatial dimension can be represented as
#### $$\frac{\partial^{2}ψ}{\partial y^{2}} = (y^{2} - ε)ψ$$
Approximating for a very large $y$ will be 
#### $$\frac{\partial^{2}ψ}{\partial y^{2}} \approx y^{2}ψ$$
So the approximate solution to the wavefunction is
#### $$ψ_{vly} = Ay^{n}e^{-y^{2}/2}$$
$Ay^{n}$ is seen as a Hermite polynomial, which is noted as $H(y)$, and is used to see what conditions are imposed on the energy of the system
#### $$\begin{gather}
ψ = H(y)e^{-y^{2}/2} \\
\frac{d^{2}H(y)e^{-y^{2}/2}}{dy^{2}} = (y^{2} - ε)H(y)e^{-y^{2}/2} \\
\frac{dψ}{dy} = -yH(y)e^{-y/2} + e^{-y^{2}/2} \frac{dH}{dy} \\
\frac{d^{2}ψ}{dy^{2}} = -He^{-y^{2}/2} - y \frac{dH}{dy}e^{-y^{2}/2} + e^{-y^{2}/2} \frac{d^{2}H}{dy^{2}}
\end{gather}$$
Evaluating the function results in the following relation
#### $$\frac{d^{2}H}{dy^{2}} - 2y \frac{dH}{dy} + (ε - 1)H = 0$$
and this is known as the *Hermite equation*. The lowest order coefficient of the polynomial is guessed to be $H$, which is a constant, which will be equated to $a_{0}$
#### $$(ε - 1)a_{0} = 0$$
So the solution for $ε$ will be 1, and for the ground state, $E_{0} = \frac{\hbarω}{2}$. The lowest order solution to the harmonic oscillator potential is 
#### $$ψ_{0} = a_{0}e^{(-mω/\hbar) x^{2}}$$
and normalizing for it will yield 
#### $$\begin{gather}
a_{0}^{2} \int_{-\infty}^{\infty} e^{(-2mω/\hbar)x^{2}} \, dx = 1 \\
a_{0}^{2} = \left( \frac{mω}{π\hbar} \right)^{1/2}
\end{gather}$$
The wavefunction evaluation with the coefficient is
#### $$ψ_{0} = \left( \frac{mω}{π\hbar} \right)^{1/4}e^{-(mω/\hbar)x^{2}}$$
For the first energy level
#### $$\begin{gather}
H_{1} = (ay + b) \\
\frac{d^{2}H_{1}}{dy^{2}} - 2y \frac{dH_{1}}{dy} + (ε - 1)H_{1} = 0 \\
\frac{dH_{1}}{dy} = a;\ \frac{d^{2}H_{1}}{dy^{2}} = 0 \\
-2ya + (ε - 1)(ay + b) = 0
\end{gather}$$
$y$ must equal zero for these systems, so the equation can be simplified to
#### $$\begin{gather}
-2a + εa - a = 0 \\
ε_{1} = 3
\end{gather}$$
So, $E_{1} = \frac{3}{2}\hbar ω$. This leads to the function to find the Hamiltonian of every level by solving for the Hermite equation
#### $$H_{n}(y) = \sum_{k = 0}^{n} a_{k}y^{k};\ ε_{n} = 2n + 1;\  E_{n} = \left( n + \frac{1}{2} \right)\hbar ω$$
and the wave nodes alternate between even and odd starting with even at the ground state. 