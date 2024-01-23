---
title: Detached-Eddy Simulation
summary: A shear-layer-adapted subgrid length scale is applied to improved delayed detached eddy simulation to alleviate the "grey area" issue, and an anisotropic-minimum-dissipation subgrid length scale is further proposed to enhance the computational accuracy on anisotropic meshes.
tags:
  - DES
date: '2023-01-24T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

A shear-layer-adapted subgrid length scale is applied to the improved delayed detached eddy simulation using the shear stress transport background model (SST-IDDES). The aim is to assess the combination of the wall-modeled LES (WMLES) branch of the SST-IDDES with the new length scale in computing attached flows, as
well as to assess the effect of the new length scale when it is applied to the SST-IDDES for mitigating the “grey area” issue through initiating a dramatic drop of eddy viscosity in the initial region of a free shear layer. The assessment is conducted through simulations of a turbulent boundary layer, a fully developed channel flow, a near-sonic turbulent jet and a backward-facing step flow. The results provide strong evidence for the conclusion that the SST-IDDES combined with the new length scale performs the same as the original SST-IDDES when its WMLES branch is applied to compute the resolved parts of an attached flow, and the combination helps mitigate the “grey area” issue of the SST-IDDES and accurately represent the K-H instability in the initial region of a free shear layer. In addition, the superiority is particularly remarkable for the simulations with coarse grids.
