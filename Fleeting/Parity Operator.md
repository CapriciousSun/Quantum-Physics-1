20250321111030

Tags:

A parity operator reverses the variables within a function, even without needing to specify the function.

## Formalism
The parity operator indicates the negative for a function with any amount of variables
#### $$\begin{gather}
\hat{Π}f(\vec{r}) = f(\vec{r}) \\
\hat{Π}f(x, y, z) = f(-x, -y, -z)
\end{gather}$$
The parity operator is linear and Hermitian. The proof of the latter is 
#### $$\int ψ_{1}^{*}(x) [\hat{Π}ψ_{2}(x)]dx = \int[\hat{Π}ψ_{1}(x)]^{*} [ψ_{2}(x)]dx$$
by transforming the left hand side
#### $$\int ψ_{1}^{*}(x) [\hat{Π}ψ_{2}(x)]dx = \int ψ_{1}^{*}(x) [ψ_{2}(-x)]dx$$
This will be integrated over infinity
#### $$\int_{-\infty}^{\infty} ψ_{1}^{*}(x) ψ_{2}(-x)dx = \int_{\infty}^{-\infty} ψ_{1}^{*}(-x) ψ_{2}(x)d(-x) = -\int_{\infty}^{-\infty} [\hat{Π} ψ_{1}(x)]^{*} ψ_{2}(x)dx = \int_{-\infty}^{\infty} [\hat{Π} ψ_{1}(x)]^{*} Ψ_{2}(x)dx$$
