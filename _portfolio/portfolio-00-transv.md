---
title: "Transversal topics"
excerpt: "Nonlinear elastodynamics, Soft solids, Finite volume method"
collection: portfolio
---

### Nonlinear elastodynamics

During my PhD studies, I also worked on the equations governing the motion of nonlinear elastic solids in one space dimension. The results are presented in a <i>Wave Motion</i> [article](/publication/2017-06-27-wamot), where I fully detailed the derivation of the analytical solution to the Riemann problem

$$
\begin{aligned}
\partial_t \varepsilon &= \partial_x v\\
\rho_0 \partial_t v &= \partial_x \sigma(\varepsilon)
\end{aligned}
\qquad\text{with}\qquad
(\varepsilon, v)|_{t=0} = \begin{cases}
(\varepsilon_L, v_L), & x<0\\
(\varepsilon_R, v_R), & x>0
\end{cases}
\notag
$$

for various constitutive laws. The solution includes shock waves, rarefaction waves and compound waves, leading to an [algorithm](http://gchiavassa.perso.centrale-marseille.fr/RiemannElasto/) to solve the problem (development of a [Matlab toolbox](https://www.mathworks.com/matlabcentral/fileexchange/63424-riemannelasto1d)). The mathematical theory behind this kind of system of partial differential equations goes back to the 1970s.

During my first post-doctoral fellowship, I had the opportunity to investigate the diffraction of an acoustic beam propagating in a soft elastic solid along a given direction (Figure). This phenomenon is described by a system of coupled KZK-type equations, for which I developed a Finite Volume code from scratch. We [published](/publication/2021-09-08-cnsns) the results in <i>Commun. Nonlinear Sci. Numer. Simul.</i>

<figure>
    <img src="/images/Elast.png" width="400" height="230" alt="Shear wave beam">
</figure>

### Soft solids

In relation with my research works on traumatic brain injury, I investigated several aspects of the modelling and characterisation of soft biological tissues. More specifically, I studied the propagation of shear waves in pre-stressed viscoelastic media, see the 2022 <i>Int. J. Solids Struct.</i> publication. Using these results, I adapted an experimental technique to measure the amount of mechanical stress in a material based on the propagation of two shear waves, see <i>Extreme Mech. Lett.</i> [paper](/publication/2024-02-23-eml). Experimental measurements are currently being performed on various samples using the theory presented in a recent <i>Math. Mech. Solids</i> [publication](/publication/2024-03-13-mms). Finally, I also became interested in the modelling of static torsional motions in soft porous solids (see study published in <i>Int. J. Non-Linear Mech.</i> [publication](/publication/2023-12-06-nlm)).

<figure>
    <img src="/images/Porous.png" width="400" height="230" alt="Soft porous cylinder">
</figure>

### Finite volume method

(In construction)