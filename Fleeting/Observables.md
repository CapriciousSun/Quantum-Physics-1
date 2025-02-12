20250124103906

Tags:

Observables are physical parts of a system that can be measured experimentally. Mathematically, this is done through operators, which are represented with letters with a hat. 

## Momentum
From the Schrodinger's equation, there are two ways to compute the momentum $Φ_{p}(p)$. Either by the Fourier transform or to express $p$ as a function of $x$. The momentum operator can be derived via the correspondence principle, where the behavior of quantum systems must be consistent with classical mechanics to a certain extent. With momentum, this yields the relationship $$\frac{d\langle x \rangle}{dt} = \frac{\langle p_{x} \rangle}{m}$$
Considering a pure momentum state $$Ψ(x, t) = Ae^{i(\frac{px - ET}{\hbar})}$$
and using the momentum operator, which is an eigenstate of momentum, and when paired with $Ψ$, gets the eigenvalue of momentum, the observable for the momentum can be derived as $$\langle p \rangle = \int A^{*}e^{-i\left(\frac{px - Et}{\hbar}\right)} \underbrace{\frac{\hbar}{i} \frac{\partial}{\partial x}}_{\text{Momentum}}Ae^{i\left(\frac{px - Et}{\hbar}\right)}dx$$
