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
* PhD in Ocean Engineering<br> 2022, _IIT Madras_, Chennai, India
* M.Tech. in Applied Mechanics<br> 2017, _IIT Madras_, Chennai, India
* B.Tech. in Naval Architecture and Ocean Engineering <br> 2017, _IIT Madras_, Chennai, India

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * GitHub University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
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
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
