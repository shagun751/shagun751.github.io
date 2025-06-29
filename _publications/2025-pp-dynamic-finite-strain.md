---
title: "Dynamic Finite-Strain Analysis of Mooring Lines Based on Tangential Differential Calculus (Under Review)"
collection: publications
category: preprints
permalink: /publication/2025-pp-dynamic-finite-strain
excerpt: '<i>Scientific Impact</i>: FEM model for catenary and taut mooring lines. Conducive to the geometric nonlinearity arising from the shape of the line, and also the large deformation of the line. Explores hardening behaviour of taut lines. Additionally, introduces low-fidely semi-analytical equivalents for taut lines for conceptual design and optimisation.'
date: 2025-06-10
# venue: 'Journal of Fluids and Structures'
#slidesurl: ''
paperurl: 'https://www.researchgate.net/publication/392154502_Dynamic_Finite-Strain_Analysis_of_Mooring_Lines_Based_on_Tangential_Differential_Calculus'
#bibtexurl: ''
directurl: 'http://dx.doi.org/10.2139/ssrn.5271454'
authors: '<b>Agarwal, S.</b>, Gómez, Sergio Sánchez & Colomés, Oriol.'
citation: '<b>Agarwal, S.</b>, Gómez, Sergio Sánchez & Colomés, Oriol. Dynamic Finite-Strain Analysis of Mooring Lines Based on Tangential Differential Calculus. Available at SSRN. (under review)'
---

This manuscript presents a formulation for mooring line dynamics using a Tangential Differential Calculus (TDC) framework. The approach handles geometric non-linearities due to both curved shapes and large deformations and is applicable to catenary and taut mooring systems. Defining the boundary value problem using TDC enables a consistent and flexible treatment of partial differential equations on curved domains. The formulation is based on finite-strain theory and includes self-weight, buoyancy, seabed interaction, and hydrodynamic drag.The formulation is numerically modelled using finite element method and implemented in Julia. Mesh and element order convergence studies show optimal performance. The model is validated against standard benchmarks and applied to catenary lines under various excitations, showing good agreement with reference results.A key focus is the dynamic behaviour of taut mooring lines under harmonic transverse excitation. Results emphasize the impact of geometric non-linearity on displacement and strain, which are observed as super-harmonics and sub-harmonics in the strain, with the system's natural frequency gradually increasing with higher excitation frequency and amplitude.The manuscript also introduces a reduced-order analytical model, suitable for low-fidelity preliminary design and optimization of taut lines. It demonstrates good accuracy up to the second natural frequency, even under high pre-tension and excitation.

| Catenary line in JONSWAP sea-state in shallow waters |
| --- |
| ![Catenary line animation](../files/mooring_agif_loc10.gif) |


| Taut line exhibiting 2nd and 3rd mode |
| --- |
| <img src="../files/ares_epsilon0=0p01_amp=0p10_freq=0p8_gif.gif" width="35%" /> <img src="../files/ares_epsilon0=0p01_amp=0p10_freq=1p2_gif.gif" width="35%" /> |


| Frequency sweep results showing the peak amplitude of the principal strain as a function of the excitation frequency for taut line in periodic excitation |
| --- |
| ![Frequency Sweep Results](../files/mooring_res.png) |

