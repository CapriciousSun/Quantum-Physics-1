20250318100917

Tags:

Dirac notation, sometimes called Bra-Ket notation, helps simplify the writing of integrals. 
## Formalism
A "bra" is $\langle Ψ|$ and a "ket" is $|Ψ\rangle$. They can be added together to form something like $\langle Q \rangle = \langle Ψ_{1} | \hat{Q} Ψ_{1}\rangle$, which can be expanded to 
#### $$\langle Q \rangle = \langle Ψ_{1} | \hat{Q} Ψ_{1}\rangle = \int_{allspace} Ψ_{1}^{*} \hat{Q} Ψ_{1}dx$$
which is the expectation value of $Ψ_{1}$ using the operator $\hat{Q}$. The matrix element of $Ψ_{1}$ and $Ψ_{2}$ are written like
#### $$\langle Ψ_{1} | \hat{Q} Ψ_{2} \rangle = \int_{allspace} Ψ_{1}^{*} \hat{Q} Ψ_{2}dx$$
The overlap integral of $Ψ_{1}$ and $Ψ_{2}$ is written like 
#### $$\langle Ψ_{1} | Ψ_{2} \rangle = \int_{allspace} Ψ_{1}^{*} Ψ_{2}dx$$

## Properties
Constants can be taken out of the Bra-Ket. For example
#### $$\begin{gather}
\langle ψ_{1} | cψ_{2}\rangle = c \langle ψ_{1} | ψ_{2} \rangle \\ \\
\langle cψ_{1} | ψ_{2} \rangle = c^{*} \langle ψ_{1} | ψ_{2} \rangle
\end{gather}$$

## Calculations of the Mean
For an operator $\hat{Q}$, the calculation of the expectation value is 
#### $$\begin{gather}
\langle Q \rangle(t) = \int Ψ^{*} \hat{Q} Ψdx = \int \left[ \sum c_{n'}(t)ψ_{n'}(x) \right]^{*} \left[ \hat{Q} \sum c_{n}(t) ψ_{n}(x) \right]dx = \int \left[ \sum c_{n'}(t)ψ_{n'}(x) \right]^{*} \left[ \hat{Q} \sum c_{n}q_{} \right]
\end{gather}$$
