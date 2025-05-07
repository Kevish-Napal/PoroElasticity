# PoroElasticity

This project simulates the scattering of poroelastic waves by cracks induced through hydraulic fracturing, using Biot’s theory of poroelasticity. The underlying system consists of a multivariate PDE capturing three rock displacement modes (two shear and one compressional) and one fluid displacement mode. The simulation is implemented in FreeFem++, a finite element solver written in C++.

The generated synthetic data has been used to validate a non-destructive testing framework for subsurface crack imaging, as presented in [Pourahmadian & Napal (2022)](https://www.sciencedirect.com/science/article/pii/S0021999122000675).


---
**Reference**

[[1]](https://www.sciencedirect.com/science/article/pii/S0021999122000675) Fatemeh Pourahmadian and Kevish Napal, Poroelastic near-field inverse scattering, Journal of Computational Physics, Volume 455, 2022, 111005. 
