20250121110958

Tags:

The probability current is a concept used in thinking about traveling particles. At every point across the wave, there's a different probability current based on the slice it's taking out of the wave. 

## Formalism
```ad-formula
#### Probability Current Density
#### $$j(x, t) = -\frac{i\hbar}{2m}\left(Ψ^{*}\frac{δΨ}{δx} - Ψ\frac{δΨ^{*}}{δx}\right) \equiv j_{x}(x)$$
```
The final form of this equation is $|A|^{2}v_{0}$. where A is the amplitude of the wave at a specific point and $v_{0}$ is the velocity of the wave. 
```ad-formula
#### Evaluate the probability current for the wave function $Ψ = Ae^{ikx + iωt} + Be^{-ikx + iωt}$
$$j_{x}(x) = -\frac{i\hbar}{2m}(A^{*}e^{-ikx} + B^{*}e^{ikx})(ikAe^{ikx} - ikBe^{-ikx})$$
$$-\frac{i\hbar}{2m}(ikA^{*}A - ikA^{*}Be^{-2ikx} + ikB^{*}Ae^{2ikx} - B^{*}Bik)$$
$$\frac{\hbar k}{2m}$$
```

For a pure momentum state where $j = kΨ^{*}Ψ$ and $E > V$, the probability current is variable
#### $$\begin{cases}
j_{incident} = +\frac{hk_{1}}{m}A^{2} \\
j_{reflected} = -\frac{hk_{1}}{m}B^{2} \\
j_{transmitted} = +\frac{hk_{2}}{m}C^{2}
\end{cases}$$
Hence, the transmitted wave is described as 
#### $$T \equiv \frac{j_{transmitted}}{j_{incident}} = \frac{k_{2}C^{2}}{k_{1}A^{2}} = \frac{k_{2}}{k_{1}}\left( \frac{2k_{1}}{k_{2} + k_{1}} \right)^{2} = \frac{4k_{1}k_{2}}{(k_{2} + k_{1})^{2}}$$
For the same pure momentum state but $E < V$ 
#### $$\begin{cases}
j_{incident} = +\frac{hk_{2}}{m}A^{2} \\
j_{reflected} = -\frac{\hbar k_{1}}{m}B^{2} = -\frac{\hbar k_{1}}{m}A^{2} \\
j_{transmitted} = -\frac{i\hbar}{2m} \left[ ψ^{*} \frac{\partialψ}{\partial x} - ψ \frac{\partialψ}{\partial x} \right] = 0
\end{cases}$$

## Solution
The general solution of a constant potential where $E > V$ is
#### $$[Ae^{ikx} + BAe^{-ikx}] e^{-(E/\hbar) t}$$
and the probability current is calculated with the above formula. 

## Physical Meaning
The probability current is a reflection of the probability of finding a wave traveling in one direction. When the probability current is 0, that means the wave is likely a standing wave, since the measurement for either direction cancels out. 

