---
layout: page
use_math: true
title: Normal Incidence
---

We learned about the boundary conditions between two materials with different permittivities last semester.  This lead us to the following set of conditions when there are no free currents or charges as is the case when an electromagnetic wave travels from one medium to another.

$$\varepsilon_1 E^{\perp}_1 = \varepsilon_2 E^{\perp}_2 \qquad \mathbf{E}^{\parallel}_1 = \mathbf{E}^{\parallel}_2$$

$$B^{\perp}_1 = B^{\perp}_2 \qquad \dfrac{1}{\mu_1}\mathbf{B}^{\parallel}_1 = \dfrac{1}{\mu_2}\mathbf{B}^{\parallel}_2$$

Consider a monochromatic, sinusoidal traveling electromagnetic wave impinging upon a surface. The wave travels in the $z$ direction and strikes the surface perpendicular to it's face. Assume it travels through a materials with a given wave speed $v_1$ and strikes a material with a given wave speed $v_2$. The incident wave is polarized in the $x$-direction (i.e., $E_I$ is in the $x$ direction).

Find the relationship between the amplitudes of the incident, reflected, and transmitted electric and magnetic fields. How do these relate to what you know about waves on strings?

To assist you, here's the form to consider for the plane waves:

#### Incident:

$$\tilde{\mathbf{E}}_I(z,t) = \tilde{E}_{0I}e^{i(k_1z-\omega t)}\hat{\mathbf{x}}$$

$$\tilde{\mathbf{B}}_I(z,t) = \dfrac{1}{v_1}\tilde{E}_{0I}e^{i(k_1z-\omega t)}\hat{\mathbf{y}}$$

#### Reflected:

$$\tilde{\mathbf{E}}_R(z,t) = \tilde{E}_{0R}e^{i(-k_1z-\omega t)}\hat{\mathbf{x}}$$

$$\tilde{\mathbf{B}}_R(z,t) = -\dfrac{1}{v_1}\tilde{E}_{0R}e^{i(-k_1z-\omega t)}\hat{\mathbf{y}}$$

#### Transmitted:

$$\tilde{\mathbf{E}}_T(z,t) = \tilde{E}_{0T}e^{i(k_2z-\omega t)}\hat{\mathbf{x}}$$

$$\tilde{\mathbf{B}}_T(z,t) = \dfrac{1}{v_2}\tilde{E}_{0T}e^{i(k_2z-\omega t)}\hat{\mathbf{y}}$$
