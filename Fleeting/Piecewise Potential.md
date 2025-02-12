20250204110156

Tags:

Problems in quantum physics can be solved by finding the instant potential for every region and matching up the solutions and derivatives at the boundaries. The solution to a time-independent Schrodinger equation in a region where $V$ is constant and $E > V$ is a system where the kinetic energy is positive $$\begin{gather*}
\frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} + (E - V)ψ(x) = 0 \\
\Downarrow \\
\frac{\hbar^{2}k^{2}}{2m} = (E - V) \implies k = \pm \sqrt{ \frac{2m(E - V)}{\hbar^{2}} }
\end{gather*}$$
On the other hand, for a time-independent Schrodinger equation where $V$ is a constant and $E < V$, the solution would look like $$\frac{\hbar^{2}}{2m} \frac{\partial^{2}ψ(x)}{\partial x^{2}} - |E - V|ψ(x) = 0$$
Like the last step, we're guessing that $ψ(x) = e^{ikx}$ $$\frac{\hbar^{2}k^{2}}{2m} = -|E - V| \implies k = \pm i\sqrt{ \frac{2m|E - V|}{\hbar^{2}} }$$

#### Intuition
Solutions for the Schrodinger equation curve toward the x-axis in classically allowed $(E > V)$ regions and away from the x-axis in classically forbidden regions. For states with boundaries, being outside of the bounds means the wavefunction is zero. Curvatures increases for larger $|E - V(x)|$. Solutions are continuous and smooth if the potential has finite steps (most physical systems). 

For a potential
#### $$V(x) = \begin{cases}
0; -\frac{a}{2} < x < \frac{a}{2} \\
1; |x| > \frac{a}{2}
\end{cases}$$

#### $$ψ(x) = \begin{cases}
Ce^{\kappa x} + De^{\kappa x} \text{ for } x < -\frac{a}{2} \\
A\sin(kx) + B\cos(kx) \text{ for } -\frac{a}{2} < x < \frac{a}{2} \\
Fe^{κx} + Ge^{-κx} \text{ for } x > \frac{a}{2}
\end{cases}$$
This is all for where $k = \left| \frac{\sqrt{ 2mE }}{\hbar}\right|$ and $K = \left| \frac{\sqrt{ 2m(V_{0} - W) }}{\hbar}\right|$. For even wavefunctions $(n = 1, 3, 5)$,
#### $$ψ_{\text{even}}(x) = \begin{cases}
Ce^{κx} \text{ for } x < -\frac{a}{2} \\
B\cos(kx) \text{ for } -\frac{a}{2} < x < \frac{a}{2} \\
Ce^{-κx} \text{ for } x > \frac{a}{2}
\end{cases}$$
and for odd wavefunctions $(n = 2, 4, 6)$ 
#### $$ψ_{\text{odd}}(x) = \begin{cases}
Ce^{κx} \text{ for } x < -\frac{a}{2} \\
B\sin(kx) \text{ for } -\frac{a}{2} < x < \frac{a}{2} \\
-Ce^{-κx} \text{ for } x > \frac{a}{2}
\end{cases}$$

For even parity states
#### $$\begin{gather*}
\frac{\left( k\sin\left( \frac{ka}{2} \right) \right)}{\cos\left( \frac{ka}{2}  \right)} = K \\
k\tan\left( \frac{ka}{2} \right) = K
\end{gather*}$$
For odd parity states
#### $$\begin{gather*}
\frac{k\cos\left( \frac{ka}{2} \right)}{-\sin\left( \frac{ka}{2} \right)} = K \\
k\cot\left( \frac{ka}{2} \right) = -K
\end{gather*}$$
For even solutions, the wavefunction must be continuous at the boundary of $x = -\frac{a}{2}$ and $x = \frac{a}{2}$. The wavefunction will look like $B\cos\left( \frac{ka}{2} \right) = Ce^{-\frac{κa}{2}}$. The derivative of the wavefunction must be continuous at the same boundaries, $Bk\sin\left( \frac{ka}{2} \right) = CKe^{-\frac{κa}{2}}$. These equations are transcendental equations that cannot be solved in closed form, but can be solved with numerical methods. 