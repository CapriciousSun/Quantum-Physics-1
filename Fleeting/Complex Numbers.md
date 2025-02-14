20250110103209

Tags: [[Mathematics]]

Complex numbers are frequently used in wavefunctions to illustrate the wave shifting in 3 dimensions. 

## Notation
Complex numbers are written as some $\tilde{z} = a + ib$, where $i$ is $\sqrt{ -1 }$ and $a$ and $b$ are the magnitude of real and imaginary numbers. In addition, $\tilde{z}$ can be rewritten in trigonometric form like $\tilde{z} = r(\cos(θ) + i\sin(θ)) = re^{iθ}$ where $r = \sqrt{ \vec{r} \boldsymbol{\cdot} \vec{r} } = \sqrt{ a^{2} + b^{2} }$, $θ = \arctan\left( \frac{y}{x} \right)$, and $j \equiv \sqrt{ 1 } = e^{\frac{iπ}{2}}$. Another rule for trigonometric transformation is  $\tilde{A}(t) = iae^{iωt} = ae^{i\frac{π}{2}}e^{iωt} = ae^{i(ωt + \frac{π}{2})}$. The trigonometric identity used for this is $$\begin{cases}
\cos(ωt) = \sin\left( ωt + \frac{π}{2} \right) \\
\sin(ωt) = \cos\left( ωt - \frac{π}{2} \right)
\end{cases}$$

## Phasor
A harmonic quantity $v = V_{0}\cos(ωt + φ)$ can be represented by a rotating vector called a phasor. The projection of a phasor on the horizontal axis is the current $I_{0}$ at the time, the frequency $f$ and angular speed $ω = 2πf$, and the length is the maximum current $I$. 
![[Pasted image 20250212184025.png|600]]
There are also a few conventions with phasors that must be abided. 
1. Phasors rotate in the counter-clockwise direction with the angular speed $ω$
2. The length of the phasor is proportional to the ac quantity amplitude
3. The horizontal projection of the phasor on the horizontal axis gives the real part of the quantity

## Complex Conjugate
The complex conjugate of a number is the negation in terms of its imaginary unit. It is noted by the dagger symbol and looks like $(a + ib)^{\dagger} = a - ib$ and $(Re^{iθ})^{\dagger} = Re^{-jθ}$. Multiplying complex conjugate with the regular form $(a + ib)(a - ib) = a^{2} + b^{2}$. Multiplying by the complex conjugate and taking the square root yields the magnitude of a complex number. Taking the complex ratio is also quite useful, since it allows for rapid determination of how much the complex number is "in-phase" and "out-of-phase". Multiplying the top and bottom of a fraction with the complex conjugate yields the separated components. For a ratio $\frac{a + ib}{c + id}$, the complex ratio would be $$\frac{a + ib}{c + id}\left( \frac{c - id}{c - id} \right) = \frac{(ac + bd) + i(-ad + bc)}{c^{2} + d^{2}} = \left( \frac{ac + bd}{c^{2} + d^{2}} \right) + i\left( \frac{-ad + bc}{c^{2} + d^{2}} \right)$$
The magnitude of a complex ratio is also useful, for an $|A| = \sqrt{ AA^{\dagger} }$, the complex magnitude is  $$\sqrt{ \left( \frac{a + ib}{c + id} \right)\left( \frac{a - ib}{c - id} \right) } = \sqrt{ \frac{a^{2} + b^{2}}{c^{2} + d^{2}} }$$
___
# References
[[Class 2 - Complex numbers – Exponential representation Wave Superposition]]
