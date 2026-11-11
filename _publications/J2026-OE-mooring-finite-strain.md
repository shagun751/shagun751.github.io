---
title: "Nonlinear Dynamic Response of Mooring Cables Based on Finite-Strain Theory: Finite Element and Reduced-Order Models"
collection: publications
category: manuscripts
permalink: /publication/J2026-OE-mooring-finite-strain
redirect_from:
  - /publication/2025-pp-dynamic-finite-strain
excerpt: '<i>Scientific Impact</i>: FEM model for catenary and taut mooring lines based on Tangential Differential Calculus, with the formulation defined on curved manifolds. Captures geometric nonlinearity arising from the shape and large deformation of the line. Explores hardening behaviour of taut lines. Additionally, introduces low-fidelity semi-analytical equivalents for taut lines for conceptual design and optimisation.'
date: 2026-08-06
venue: 'Ocean Engineering'
#slidesurl: ''
paperurl: 'https://www.researchgate.net/publication/411851332_Nonlinear_dynamic_response_of_mooring_cables_based_on_finite-strain_theory_Finite_element_and_reduced-order_models'
#bibtexurl: ''
directurl: 'https://doi.org/10.1016/j.oceaneng.2026.127337'
authors: '<b>Agarwal, S.</b>, Gómez, S. S., Colomés, O.'
citation: '<b>Agarwal, S.</b>, Gómez, S. S., Colomés, O. 2026. Nonlinear Dynamic Response of Mooring Cables Based on Finite-Strain Theory: Finite Element and Reduced-Order Models. Ocean Engineering 365, 127337.'
---

This manuscript presents a formulation for mooring line dynamics using a Tangential Differential Calculus (TDC) framework. The approach handles geometric non-linearities due to both curved shapes and large deformations and is applicable to catenary and taut mooring systems. Defining the boundary value problem using TDC enables a consistent and flexible treatment of partial differential equations on curved domains. The formulation is based on finite-strain theory and includes self-weight, buoyancy, seabed interaction, and hydrodynamic drag. The formulation is numerically modelled using finite element method and implemented in Julia. Mesh and element order convergence studies show optimal performance. The model is validated against standard benchmarks and applied to catenary lines under various excitations, showing good agreement with reference results. A key focus is the dynamic behaviour of taut mooring lines under harmonic transverse excitation. Results emphasize the impact of geometric non-linearity on displacement and strain, which are observed as super-harmonics and sub-harmonics in the strain, with the system's natural frequency gradually increasing with higher excitation frequency and amplitude. The manuscript also introduces a reduced-order analytical model, suitable for low-fidelity preliminary design and optimization of taut lines. It demonstrates good accuracy up to the second natural frequency, even under high pre-tension and excitation.

| Catenary line in JONSWAP sea-state in shallow waters |
| --- |
| ![Catenary line animation](../files/mooring_agif_loc10.gif) |


| Taut line exhibiting 2nd and 3rd mode |
| --- |
| <img src="../files/ares_epsilon0=0p01_amp=0p10_freq=0p8_gif.gif" width="35%" /> <img src="../files/ares_epsilon0=0p01_amp=0p10_freq=1p2_gif.gif" width="35%" /> |


| Frequency sweep results showing the peak amplitude of the principal strain as a function of the excitation frequency for taut line in periodic excitation |
| --- |
| ![Frequency Sweep Results](../files/mooring_res.png) |

