---
title: "Theoretical and computational results in nonlinear elastodynamics"
excerpt: "Mathematical physics, Riemann problem, Sound beams"
collection: portfolio
---

During my PhD studies, I also worked on the equations governing the motion of nonlinear elastic solids in one space dimension. The results are presented in a <i>Wave Motion</i> article (2017) [link](https://harold-berjamin.github.io/publication/2017-06-27-wamot), where I fully detailed the derivation of the analytical solution to the Riemann problem

$$
\left\lbrace
\begin{aligned}
\partial_t \varepsilon &= \partial_x v\\
\rho_0 \partial_t v &= \partial_x \sigma(\varepsilon)
\end{aligned}
\right.
\qquad\text{with}\qquad
(\varepsilon, v)^\top|_{t=0} = \begin{cases}
(\varepsilon_L, v_L)^\top, & x<0\\
(\varepsilon_R, v_R)^\top, & x>0
\end{cases}
\notag
$$

for various constitutive laws. The solution includes shock waves, rarefaction waves and compound waves, leading to an [algorithm](http://gchiavassa.perso.centrale-marseille.fr/RiemannElasto/) to solve the problem (development of a [Matlab toolbox](https://www.mathworks.com/matlabcentral/fileexchange/63424-riemannelasto1d)). The mathematical theory behind this kind of system of partial differential equations goes back to the 1970s.

During my first post-doctoral fellowship, I had the opportunity to investigate the diffraction of an acoustic beam propagating in a soft elastic solid along a given direction. This phenomenon is described by a system of coupled KZK-type equations, for which I developed a Finite Volume code from scratch. We published the results in <i>Communications in Nonlinear Science and Numerical Simulation</i> (2021) [link](https://harold-berjamin.github.io/publication/2021-09-08-cnsns).

<figure src='/images/Elast.png'>