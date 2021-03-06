---
title: "Improvements in MLPG formulation for 3D wave interaction with fixed structures"
authors:
- Shagun Agarwal
- V. Sriram
- Shiqiang Yan
- K. Murali
date: "2021-03-30T00:00:00Z"
doi: "10.1016/j.compfluid.2020.104826"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers and Fluids, 218"
publication_short: ""

abstract: This paper presents new developments in meshless local Petrov-Galerkin with Rankine source (MLPG_R) particle based method for studying interaction of waves with fixed structures in a numerical wave-tank. A new 3D formulation of the Lagrangian flow problem for incompressible fluid with optimised solution strategy is presented. The pressure Poisson equation is solved in local weak-form with integration done semi-analytically using a new symmetric expression. The wave-generation is done using one-way coupling with a 2D fully-nonlinear potential theory based finite-element model. Further a simple identification method for free-surface particles is proposed, which is shown to work well in vicinity of the structure. The solid-wall boundary condition is treated using ghost and mirror particles for accurate calculation of gradients. The waterline on domain boundary faces is treated using a tangentially moving side-wall approach which makes this particle based scheme capable of capturing small amplitude waves and focusing waves. The paper briefly presents experimental setup used for studying the interaction of a fixed emergent cylinder with uni-directional regular and focusing waves in 3D. The numerical model is validated against results from this experiment. An analysis is conducted on parameters related to local integration domain, wave-making coupling algorithm, particle distribution and time-step. This work highlights the use of hybrid approach for efficient and accurate simulation of waves-structure interaction.

# Summary. An optional shortened abstract.
summary: Developments and analysis on the MLPG method in 3D for interaction of steep non-breaking focusing waves with fixed cylinder.

tags:
- Publications
featured: true

# links:
# - name: ""
#   url: ""
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: [artificial-intelligence]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---


{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
