# Thermal Radiation
All objects with a temperature above absolute zero emit electromagnetic radiation. Electromagnetic radiation covers the whole spectrum: from gamma rays all the way to radio waves. The definition of each type of radiation is based on wavelength, and can be seen in [](#fig:wavelengths) 

% A figure of a photograph of some mountains, followed by a caption
:::{figure} ../figures/radiationspectrum.png
:label: fig:wavelengths
:width: 80%
Electromagnetic radiation spectrum
:::

## Planck's Law

The spectral emissive power of a blackbody is

$$
E_\lambda
=
\frac{2\pi hc^2}
{\lambda^5
\left(
e^{hc/\lambda kT}
-1
\right)}
$$

where

- $h$ = Planck constant
- $c$ = speed of light
- $k$ = Boltzmann constant
- $T$ = temperature

---

## Wien's Displacement Law

The wavelength corresponding to the maximum emissive power is

$$
\lambda_{max}
T
=
2.898\times10^{-3}
\;mK
$$

As temperature increases, the peak shifts towards shorter wavelengths.

---

## Stefan-Boltzmann Law

The total emissive power equals

$$
E=\sigma T^4
$$

where

$$
\sigma
=
5.670\times10^{-8}
\;W/m^2K^4
$$

The area under the Planck curve therefore grows very rapidly with temperature.


Open the interactive Planck curve explorer:

[Planck Curve Explorer](../interactive/WIDG_Planck_Wien)
