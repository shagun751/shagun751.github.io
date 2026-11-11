---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **PhD in Ocean Engineering**, IIT Madras, India<br> 2017 – 2022<br> _Wave-structure interaction by coupled Boussinesq (FEM) and Navier-Stokes (particle-based) models in 3D_
* **M.Tech. in Applied Mechanics** (Dual Degree), IIT Madras, India<br> 2015 – 2017
* **B.Tech. in Naval Architecture and Ocean Engineering** (Dual Degree), IIT Madras, India<br> 2012 – 2017, Minor in Systems Engineering

Work experience
======
* **R&D Engineer**, Vibrotwist B.V., Delft, The Netherlands<br> Mar 2026 – present<br> Pile–soil interaction modelling for vibratory pile driving.
* **Postdoctoral Researcher**, TU Delft, The Netherlands<br> Nov 2022 – Feb 2026<br> Hydroelasticity of floating structures, floating solar platforms, synthetic mooring lines, wave run-up on monopiles.<br> Co-lecturer for the MSc course [Floating and Submerged Structures (CIEM4230)](/teaching/CIEM4230/).
* **Visiting Researcher**, City, University of London, UK<br> 2019 and 2022<br> Meshless methods for wave–structure interaction.
* **Part-time Consultant**, Planys Technologies, Chennai, India<br> 2018 – 2019<br> Propeller design and testing for an underwater ROV.
* **Part-time Research Assistant**, IIT Madras, India<br> 2014 – 2017<br> ROVs and crawlers for non-destructive inspection.

Research projects
======
* [SkyBox Phase 2](https://projecten.topsectorenergie.nl/projecten/skybox-phase-2-38300): offshore access platform (RVO, with Sif Group). Lead Researcher, 2025 – 2026
* [Hydroelastic Black Holes for Offshore Renewable Energy](https://www.nwo.nl/en/projects/ocenwxs242127) (NWO). Lead Researcher, 2024 – 2026
* [Merganser](https://solarduck.tech/merganser-pilot/): offshore floating solar demonstrator, mooring work package (RVO DEI+). Researcher, 2023 – 2024
* [Hydro-electro-elasticity of flexible wave energy converters](https://www.nwo.nl/en/projects/ocenwxs221051) (NWO). Lead Researcher, 2022 – 2023
* Beyond Open Interactive Textbooks: open JupyterBook for CIEM4230 (TU Delft). Co-developer, 2025

Awards and fellowships
======
* Prof. U.C. Kothyari Best PhD Thesis Award, Indian Society for Hydraulics, 2022
* Prime Minister's Research Fellowship (PMRF), Ministry of Education, India, 2018
* Research visit grants to the UK: SPARC, Ministry of Education, India (2022); DST India and UKRI (2019)
* Innovative Student Project Grant, IIT Madras, 2014
* Kishore Vaigyanik Protsahan Yojana (KVPY) Fellowship, DST, India, 2011

Patent
======
* Saikiran, N.T., **Agarwal, S.**, Rajagopal, P., et al. [Remotely operable underwater robotic systems](https://ip.iitm.ac.in/emerging-technologies/other-technologies/idf-no-1470-remotely-operable-underwater-robotic-systems). Indian Patent 516897, granted 2024.

Skills
======

* **Programming**: FORTRAN (Advanced), C/C++ (Moderate), Julia (Moderate), OpenMP (Advanced), Python (Moderate), OpenACC (Moderate), MPI (Basic)
* **Numerical methods**: Finite Element (Advanced), Meshless (Advanced), Finite Difference (Moderate)
* **Simulation**: ANSYS Fluent (Moderate), STAR-CCM+ (Moderate), OpenFOAM (Moderate)
* **Analysis and Presentation**: MATLAB (Moderate), Mathematica (Moderate), Paraview (Moderate), Tecplot (Basic), Inkscape (Moderate)
* **Others**: LaTeX (Advanced), MS Office (Moderate), git (Moderate), AutoCAD (Basic)

Journal Publications
======
  <ol reversed>
  {% for post in site.publications reversed %}
    {% if post.categories contains "manuscripts" %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ol>  
  
Talks
======
  <ol reversed>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ol>
  
Teaching
======
  <ul>{% assign courses = site.teaching | sort: "date" | reverse %}{% for course in courses %}
    <li><a href="{{ course.url }}">{{ course.title }}</a>, {{ course.type }}, {{ course.venue }}, {{ course.period }}</li>
  {% endfor %}</ul>

Supervision
======
Co-supervised 9 MSc theses at TU Delft. See the [full list](/supervision/).
