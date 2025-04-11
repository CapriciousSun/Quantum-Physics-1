20250124103906

Tags:

Observables are physical parts of a system that can be measured experimentally. Mathematically, this is done through operators, which are represented with letters with a hat. 

## Momentum
From the Schrodinger's equation, there are two ways to compute the momentum $Φ_{p}(p)$. Either by the Fourier transform or to express $p$ as a function of $x$. The momentum operator can be derived via the correspondence principle, where the behavior of quantum systems must be consistent with classical mechanics to a certain extent. With momentum, this yields the relationship $$\frac{d\langle x \rangle}{dt} = \frac{\langle p_{x} \rangle}{m}$$
Considering a pure momentum state $$Ψ(x, t) = Ae^{i(\frac{px - ET}{\hbar})}$$
and using the momentum operator, which is an eigenstate of momentum, and when paired with $Ψ$, gets the eigenvalue of momentum, the observable for the momentum can be derived as $$\langle p \rangle = \int A^{*}e^{-i\left(\frac{px - Et}{\hbar}\right)} \underbrace{\frac{\hbar}{i} \frac{\partial}{\partial x}}_{\text{Momentum}}Ae^{i\left(\frac{px - Et}{\hbar}\right)}dx$$

## Commuting
The commutator is the combination of two operators in which the difference of two operators done in different order. 
#### $$[A_{op}, B_{op}] \equiv (A_{op}B_{op} - B_{op}A_{op})$$
Whether or not two operators commute gives information regarding the nature of eigenfunctions of operators. A complete set of simultaneous eigenfunction of two operators exist if the operators commute. If they do not commute, then their result $iC_{op}$ is a Hermitian operator, and the relation 
#### $$ΔAΔB ≥ \left| \frac{\langle C \rangle}{2} \right|$$
must be true. This is called the generalized uncertainty relation.
#### Example
The Parity operator $Π$ and the Hamiltonian for a symmetric potential commute, and it is shown by solving for the both of them
#### $$\begin{gather}
[H_{SYM}, Π] = \left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}} + V(x) \right)ΠΨ(x) - Π\left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}} + V(x) \right)Ψ(x) \\ \\
= \left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}} + V(x) \right)Ψ(-x) - \left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial (-x)^{2}} + V(-x) \right)Ψ(-x) \\ \\
= \left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}} + V(x) \right)Ψ(-x) - \left( -\frac{\hbar^{2}}{2m} \frac{\partial^{2}}{\partial x^{2}} + V(x) \right)Ψ(-x) = 0
\end{gather}$$

#### Example
The position and momentum operators do not commute
#### $$[p_{op}, x]ψ = -i\hbar \frac{\partial}{\partial x}(xψ) - x\left( -i\hbar \frac{\partial}{\partial x}ψ \right) = -i\hbar\left( \frac{\partial}{\partial x}(xψ) - x \frac{\partial}{\partial x}ψ \right) = -i\hbar\left\{ \left( ψ + x \frac{\partialψ}{\partial x} \right) -  \right\}$$