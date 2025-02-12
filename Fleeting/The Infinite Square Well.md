20250124114249

Tags:

This applies to a system where within the well, the potential energy is 0, but when outside of the well, the potential is infinite. This obeys continuity, but disobeys smoothity. 

## Formalism
It's defined as $$ψ(x = L - ε) = ψ(x = L + ε)$$
Here, the boundary conditions of the well are defined by a [[Waves|wave function]] where $$ψ = Ae^{-ikx} - Be^{ikx}$$
and $$Ψ(x, t) = (Ae^{-i(kx)} + Be^{i(kx)})e^{-iωt}$$

## Boundary Conditions
$$ψ(x) = 0$$
$$ψ(0) = 0$$
$$ψ(x) = A(e^{i(kx)} - e^{i(kx)}) \propto  -A\sin(kx)$$
$$ψ(L) = 0 \rightarrow A\sin(ka) = 0 \rightarrow ka = nπ$$
$$k_{n} = n \frac{π}{a}$$
where $n$ is an integer.

## Operators
Within the square well $(V = 0)$, there is some Schrodinger equation that satisfies the boundary condition. A wave function that would satisfy the condition would have $$Ψ_{n} = \sqrt{ \frac{2}{L} }\sin\left( \frac{nπx}{L} \right);\ E_{n} = \frac{\hbar^{2}π^{2}n^{2}}{2mL^{2}}$$
where $n$ is the excited state that the particle is at, 1 being the ground state. With a quantized energy and wave, the wave function will look like $$Ψ(x, t) = \sqrt{ \frac{2}{L} }\sin\left( \frac{nπx}{L} \right)e^{i \frac{E}{\hbar}t}$$

## Kinetic Energy
A measure of the kinetic energy as well as the "depth" in the well is denoted by $ξ$, and it uses the energies found in [[Piecewise Potential|piecewise potential]]. The system of the kinetic energy is 
#### $$\begin{cases}
ξ = \frac{ka}{2} \text{ (kinetic energy) } \\
ξ_{0} = \frac{a}{\hbar}\sqrt{ \frac{mV}{2} } \text{ (depth)}
\end{cases}$$
If this were the case, then even solutions of potential is $\tan(ξ) = \frac{\sqrt{ ξ_{0}^{2} - ξ^{2} }}{ξ}$, whereas the odd solution of potential is $-\cot(ξ) = \frac{\sqrt{ ξ_{0}^{2} - ξ^{2} }}{ξ}$. For both of these solutions, there are a few rules. 
	1. Intersections are allowed energies
	2. Every time even and odd are about to switch, they go to $\infty$
	3. If well depth is too shallow, only one solution can be found for even and no solutions can be found for odd
	4. If well depth is too deep, solutions approach the infinite well
