---
title: "Beyond Taylor's hypothesis: a novel volumetric reconstruction of velocity and density fields for variable‑density and shear flows"
authors:
- Dominique Fratantonio
- admin
- John Charonko
- Kathy Prestridge
date: "2021-Mar-31T00:00:00Z"
doi: "https://doi.org/10.1007/s00348-021-03156-0"

# Schedule page publish date (NOT publication's date).
publishDate: "2021-03-31T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Experiments in Fluids, 62*: 84"
publication_short: "Exp Fluids"

abstract: This work presents a novel numerical procedure for reconstructing volumetric density and velocity fields from planar laser-induced fluorescence (PLIF) and stereoscopic particle image velocimetry (SPIV) data. This new method is theoretically and practically demonstrated to provide more accurate 3D vortical structures and density fields in high shear flows than reconstruction methods based on the mean convective velocity. While Taylor's hypothesis of frozen turbulence is commonly applied by using the local mean streamwise velocity, the proposed algorithm uses the measured local instantaneous velocity for data convection. It consists of a step-by-step reconstruction based on a mixed Lagrangian–Eulerian solver that includes the 3D interpolation of scattered flow data and that relaxes the Taylor's hypothesis by iterative enforcement of the incompressibility constraint on the velocity field. This methodology provides 3D fields with temporal resolution, spatial resolution, and accuracy comparable to that of real 3D snapshots, thus providing a practical alternative to tomographic measurements. The procedure is validated using numerical data of the constant-density channel flow available on the Johns Hopkins University Turbulence Database (JHTDB), showing the accurate reconstruction of the 3D velocity field. The algorithm is applied to an experimental dataset of PLIF and SPIV measurements of a variable-density jet flow, demonstrating its capability to provide 3D velocity and density fields that are more consistent with the Navier–Stokes equations compared to the mean flow convective method.


# Summary. An optional shortened abstract.
summary: This work presents a novel numerical procedure for reconstructing volumetric density and velocity fields from planar laser-induced fluorescence (PLIF) and stereoscopic particle image velocimetry (SPIV) data.

tags:


featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
