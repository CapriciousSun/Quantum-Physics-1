20250228100828

Tags:

When a particle enters a region where $E < V$, the wavefunction will begin to decay until it dissipates. The total change is an exponential decay and caused by the negative difference in energy. For a incident wave $Ae^{ikx - iωt}$ and reflected wave $Be^{-ikx - iωt}$, it would result in the relationship 
#### $$B = \frac{ik_{1} + K}{ik_{1} - K}A$$
The total energy would be 
#### $$Ae^{ikx - iωt} + \frac{ik_{1} + K}{ik_{1} - K}Ae^{-ikx - iωt}$$
It would appear as if the wavefunction extends into the barrier with a higher potential, despite the fact that it shouldn't have gotten past the barrier. This effect is called quantum tunneling. 

## Current
The transmission coefficient for $E < V_{0}$ is
#### $$T = \frac{j_{t}}{j_{i}} = 16 \frac{E}{V_{0}}\left( 1 - \frac{E}{v_{0}} \right) e^{-2k_{2}a}$$
where $j_{t}$ is current of transmission and $j_{t}$ is current of incidence and $k_{2} = \sqrt{ \frac{2m (V - E}{\hbar^{2}}) }$. For a region where $E > V_{0}$, the transmission coefficient becomes
#### $$T = \frac{1}{1 + \frac{\sin^{2}k_{3}a}{4 \frac{E}{V_{0}} \left( \frac{E}{V_{0}} - 1 \right)}}$$

#### Example
The probability density in a model of barrier penetration shows that a wave where the energy of the wave is lower than the energy of the potential. The coefficient is always $|\hat{A}|^{2}$. 

## Cases
For a system where $E < V_{0}$
#### $$ψ(x) = \begin{cases}
Ae^{ik_{1}x} + Be^{-ik_{1}x}, x < 0 \\
Ce^{-k_{2}x} + De^{k_{2}x}, 0 < x < a \\
\hat{A}e^{ik_{1}x} + \hat{B}e^{-ik_{1}x}, x > a
\end{cases}$$
It is assumed that $Ae^{ikx}$ means $Ae^{ikx - iωt}$, since it is a traveling wave, hence, possessing some time dependence. This system solved for the wave numbers $k_{1}$ and $k_{2}$ would yield 
#### $$\begin{cases}
k_{1} = \frac{\sqrt{ 2mE }}{\hbar} \\
k_{2} = \frac{\sqrt{ 2m(V_{0} - E) }}{\hbar}
\end{cases}$$
A wavefunction that looks like a sinusoidal wave that transitions to an exponential decay that transitions back into a sinusoidal wave will be observed when a particle goes into a potential well with higher potential than the energy of the particle and then exits the potential well. Assume that $\hat{B} = 0$ for $x > a$, where $a$ is the exit of the potential well. The wavefunction would be in the system 
#### $$\begin{rcases}
ψ(0) \text{ continuous} \\
ψ'(0) \text{ "}
\end{rcases}\text{ at } x = 0$$
as well as
#### $$\begin{rcases}
ψ(a) \text{ continuous} \\
ψ'(a) \text{ "}
\end{rcases}\text{ at } x = a$$
