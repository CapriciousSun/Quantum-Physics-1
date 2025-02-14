20250110112025

Tags:

Waves are repeating sinusoidal movement. They are expressed in sine waves typically. 

## Harmonic Waves
Harmonic waves have their x and y positions defined as below.
```ad-formula
#### Harmonic Wave Formulas
$$y = Asin(k(x±vt) + φ)$$
$$x = Asin(kx ± ωt + ψ)$$
```

Some definitions to be made are $k$ and $ω$, which are the wave number and angular frequency of the wave. They are defined as $\frac{2π}{λ}$ and $\frac{2π}{T} = 2πv$ respectively. The phase velocity of a wave is the speed at which the constant phase moves through the system, and it's defined as $\frac{ω}{k} = λv$, where $v$ is the frequency of the wave. 

## Complex Representation
Arithmetics with waves are typically done with their complex representations, like $e^{iθ} = \cos(θ) + i\sin(θ)$. For each trigonometric break down, it creates $$\begin{cases}
\cos(θ) = \frac{e^{iθ} + e^{-iθ}}{2} \\
\sin(θ) = \frac{e^{iθ} - e^{iθ}}{2i}
\end{cases}$$
A traveling harmonic wave can in turn be represented as $$\begin{cases}
ψ(x, t) = A\cos(kx - ωt + ε) \\
ψ(x, t) = \mathrm{Re}[Ae^{i(kx - ωt + ε)}]
\end{cases}$$

## Addition
For two harmonic waves, the addition of the waves with the same wavelength and direction, but different phases is done with trigonometric identities. 
```ad-formula
#### Adding Waves Using Trigonometric Identities
#### $$ψ_{1} = ψ_{01}sin(kx + ωt + φ_{1})$$
#### $$ψ_{2} = ψ_{02}sin(kx + ωt + φ_{2})$$
#### $$ψ_{T} = ψ_{1} + ψ_{2} + ψ_{T0}sin(kx + ωt + α)$$
#### $$|ψ_{T0}^{2}| = ψ_{01}^{2} + ψ_{02}^{2} + 2ψ_{01}ψ_{02}cos(ψ_1 - ψ_2)$$
#### $$\text{tan}(α) = \frac{ψ_{01}sin(ψ_{1}) + ψ_{02}sin(ψ_{2})}{ψ_{01}cos(ψ_{1}) + ψ_{02}cos(ψ_{2})}$$
```
This sum displays interference between the two waves.

```ad-formula
#### Adding Waves Using Complex Representation
#### $$\begin{cases} ψ_{1} = ψ_{01}e^{i(kx + ωt + φ_{1})} \\ ψ_{2} = ψ_{02}e^{i(kx + ωt + φ_{2})} \end{cases}$$
#### $$ψ_{T} = e^{iωt}(ψ_{01}e^{iφ_{1}} + ψ_{02}e^{iφ_{2}})$$
#### $$ψ_{T} = e^{i(ωt + \frac{φ_{1} + φ_{2}}{2})}\left[ ψ_{01}e^{-\frac{i(φ_{2} - φ_{1})}{2}} + ψ_{02}e^{\frac{i(φ_{2} - φ_{1})}{2}} \right]$$
#### $$ψ_{T} = e^{i(ωt + \frac{φ_{1} + φ_{2}}{2})}\left[ ψ_{01}e^{-i\frac{δ}{2}} + ψ_{02}e^{i\frac{δ}{2}} \right]$$
where $δ = (φ_{2} - φ_{1})$
#### $$ψ_{T}ψ_{T}^{\dagger} = ψ_{01}^{2} + ψ_{02}^{2} + ψ_{01}ψ_{02}e^{-2i\frac{δ}{2}} + ψ_{01}ψ_{02}e^{2i\frac{δ}{2}}$$
and using $\cos(δ) = \frac{(e^{iδ} + e^{-iδ})}{2}$ 
#### $$ψ_{T}ψ_{T}^{\dagger} = ψ_{01}^{2} + ψ_{02}^{2} + 2ψ_{01}ψ_{02}\cos(δ)ψ$$
```

## Dependencies
There are two kinds of dependencies a time-dependent wave has, one of time and another of space, expressed as $ωt$ and $kt$ respectively. 

## Dispersion Relation
The angular frequency and wavelength of a wave are related to each other, and that relation is called the dispersion relation. 

## Fourier Transform
The Fourier transform is integral to wave functions, since they break down complex waves into simple perfect waves. 

## Group Velocity
An individual wave peak may be traveling in one direction, but the overall wave packet, a collections of waves, may be moving in another direction. The speed at which the wave packet is moving is called the group velocity. For a wave packet $$ψ(x, t) = \int A(k)e^{-i(kx - ωkt)}dk$$
and that A(k) has a few important values, $ω(k)$ can be expanded to the following form $$ω(k) \approxeq ω(k_{0}) + (k - k_{0})\left( \frac{dω}{dk} \right)_{k_{0}} + \dots$$
For a $k' = k - k_{0}$, the above wave packet equation can be expanded to $$ψ(x, t) = e^{i(k_{0}x - ωk_{0}t)}\int dk' e^{-ik'\left[x - \{\frac{dω}{dk}t\}\right]_{0}}$$
Following the expansion, it can be derived that the group velocity of the packet is $$v_{g} = \frac{dω}{dk}$$

