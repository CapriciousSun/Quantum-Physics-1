20250408101905

Tags: 

Angular momentum of a particle is 

## Formalism
The Hamiltonian of a particle includes kinetic energy and potential. So, the momentum term can be broken up into radial and tangential components.
#### $$p^{2} = p_{x}^{2} + p_{y}^{2} + p_{z}^{2} = p_{r}^{2} + p_{t}^{2}$$
The tangential momentum can be rewritten in terms of its angular momentum
#### $$p_{t} = \frac{L}{r}$$
which can be put back into the Hamiltonian
#### $$\frac{p_{r}^{2}}{2m} + \frac{L^{2}}{2mr^{2}} + V = E$$

## Laplacian Version
The Laplacian version of the Hamiltonian uses an operator $\hat{L}$.
#### $$\hat{L}^{2}ψ = L^{2}ψ$$
In classical mechanics, the angular momentum $\vec{L} = \vec{r} \times \vec{p}$. So, taking the cross product would yield all the angular momentums in terms of the axes.
#### $$\begin{array}{}
\vec{L} = \vec{r} \times \vec{p} = \begin{vmatrix}
i & j & k \\
x & y & z \\
p_{x} & p_{y} & p_{z}
\end{vmatrix} \\
L_{x} = yp_{z} - zp_{y} = \frac{\hbar}{i}\left( y \frac{\partial}{\partial z} -  z \frac{\partial}{\partial y}\right) \\
L_{y} = zp_{x} - xp_{z} = \frac{\hbar}{i}\left( z \frac{\partial}{\partial x} - x \frac{\partial}{\partial z} \right) \\
L_{z} = xp_{y} - yp_{x} = \frac{\hbar}{i}\left( x \frac{\partial}{\partial y} - y \frac{\partial}{\partial x} \right)
\end{array}$$
These relations can be converted to their radial forms.
#### $$\begin{array}{}
L_{x} = \frac{\hbar}{i}\left( -\sin(φ) \frac{\partial}{\partial θ} - \cot(θ)\cos(φ) \frac{\partial}{\partial φ} \right) \\
L_{y} = \frac{\hbar}{i}\left( -\cos(φ) \frac{\partial}{\partial θ} - \cot(θ)\sin(φ) \frac{\partial}{\partial φ} \right) \\
L_{z} = \frac{\hbar}{i}\left( \frac{\partial}{\partial φ} \right)
\end{array}$$

## Commutation


## Spherical Coordinates
The angular momentum of spherical coordinates is the formula below.
#### $$\hat{L}^{2} = -\hbar^{2}\left( \frac{\partial^{2}}{\partial θ^{2}} + \cot(θ) \frac{\partial}{\partial θ} + \frac{1}{\sin^{2}(θ)} \frac{\partial^{2}}{\partial φ^{2}} \right)$$
Angular momentum in a particle is indeed quantized, following the energy states of the particle. The physical manifestation of the angular momentum is the magnetic dipole moment with $L$ charge on a particle. 