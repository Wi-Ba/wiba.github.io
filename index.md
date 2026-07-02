# Thermal radiation
BLABLA
All objects with a temperature above absolute zero emit electromagnetic radiation. Electromagnetic radiation covers the whole spectrum: from gamma rays all the way to radio waves. The definition of each type of radiation is based on wavelength, and can be seen in [](#fig:wavelengths) 

% A figure of a photograph of some mountains, followed by a caption
:::{figure} radiationspectrum.png
:label: fig:wavelengths
:width: 80%
Electromagnetic radiation spectrum
:::

Thermal radiation refers to a specific wavelength range, where radiation

```{button-link} Planck2
:color: primary
Open Interactive Planck Curve Explorer
```
# Thermal Radiation

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





# Introduction

I am a book about ... something! Wikipedia has [information about books](wiki:book): hover over the link for more information.

% An admonition containing a note
:::{note}
Books are usually written on paper ... But Jupyter Book can create _websites_!
:::

If you sold 100 books at \$10 per book, you'd have \$1000 dollars according to [](#eq:book). If instead you publish your Jupyter Book to the web for free, you'd have \$0 dollars!

% An arbitrary math equation
:::{math}
:name: eq:book

x \times y = z
:::

Sometimes when reading it is helpful to foster a _tranquil_ environment. The image in [](#fig:mountains) would be a perfect spot!

% A figure of a photograph of some mountains, followed by a caption
:::{figure} https://github.com/rowanc1/pics/blob/main/mountains.png?raw=true
:label: fig:mountains

A photograph of some beautiful mountains to look at whilst reading.
:::
