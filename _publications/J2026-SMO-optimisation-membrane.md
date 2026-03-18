---
title: "Adjoint-based PDE-constrained optimization of viscoelastic floating membrane for maximum wave power absorption."
collection: publications
category: manuscripts
permalink: /publication/J2026-SMO-optimisation-membrane
excerpt: '<i>Scientific Impact</i>: Insights into the properties such as mass, pre-tension and material damping of viscoelastic floating membranes, optimised for absorbing / dissipating the maximum wave energy through hydro-visco-elastic response.<br><i>My contribution</i>: Developed the underlying FEM model. Guided the systematic analysis of the optimisation problem.'
date: 2026-02-26
# venue: 'Journal of Fluids and Structures'
#slidesurl: ''
paperurl: 'https://www.researchgate.net/publication/401260919_Adjoint-based_PDE-constrained_optimization_of_viscoelastic_floating_membrane_for_maximum_wave_power_absorption_Adjoint-based_PDE-constrained_optimization_of_viscoelasticK_El_Sayed_et_al'
#bibtexurl: ''
directurl: 'https://doi.org/10.1007/s00158-026-04270-5'
authors: 'El Sayed, K., <b>Agarwal, S.</b>, Colomés, O., Metrikine, A. V.'
citation: 'El Sayed, K., <b>Agarwal, S.</b>, Colomés, O., Metrikine, A. V. 2026. Adjoint-based PDE-constrained optimization of viscoelastic floating membrane for maximum wave power absorption. Structural and Multidisciplinary Optimization 69, 71.'
---

Viscoelastic floating membranes can be used as flexible wave breakers to protect coastal and offshore structures or as flexible wave energy converters. Despite their potential, the role of viscoelastic floating membranes in optimally harvesting or dissipating wave energy remains largely unexplored, particularly regarding how spatially varying material properties influence their performance. To address this gap, we develop an adjoint-based PDE-constrained optimization framework, built on a monolithic finite element formulation of the coupled fluid–structure interaction problem, to investigate and optimize the viscoelastic properties of floating membranes. This methodology enables a systematic optimization of design parameters such as the mass, tension, and damping, which govern the response of the membrane at different wave conditions. In this study we demonstrate that the proposed methodology allows for the optimization of homogeneous and inhomogeneous properties of membranes for different wave excitation frequencies, leading to significant improvements in energy absorption. The framework is implemented in Julia using the Gridap package ecosystem, which enables automatic differentiation of adjoints and avoids the need to derive complex adjoint formulations.
