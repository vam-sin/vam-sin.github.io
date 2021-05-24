---
title: "Efficient Cryo-Electron Tomogram Simulation of Macromolecular Crowding with Application to SARS-CoV-2"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Sinuo Liu
- Yan Ma
- Xiaojuan Ban
- Xiangrui Zeng
- admin
- Ajinkya Chaudhari
- Min Xu

# Author notes (optional)
author_notes:
-
-
- Corresponding Author
-
- 
-
- Corresponding Author

date: "2020-11-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In IEEE International Conference on Bioinformatics and Biomedicine
publication_short: In *IEEE BIBM 2020*

abstract: 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: Manuscript
  url: https://www.computer.org/csdl/proceedings-article/bibm/2020/09313185/1qmfUw4iPgA

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
  caption: 'Workflow and architecture of DeepCys'
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

We propose an efficient method for simulating a cryo-Electron Tomography (cryo-ET) image of a target macro-molecule with several neighbor macromolecules packed to achieve a realistic crowded cytoplasm content. The simulated results are subtomograms with corresponding noise-free 3D density maps and pre-specified labels (PDB ID, center locations, and orientations) to assist bioimage analysis. They can serve as benchmark datasets for testing developing cryo-ET analysis algorithms and as training datasets with readily available ground truth labels for learning neural network models. The COVID-19 pandemic has sparked a global health crisis that severely impacting lives worldwide. As an important application, we simulated the scene of SARS-CoV-2 interacting with the host cell. The simulated cryo-ET images clearly showed the binding domain of the virus and the host cell to facilitate the research of SARS-CoV-2’ infection. We also trained two different classification models to demonstrate that our simulated cryo-ET data is able to assist the cryo-ET analysis task and to validate the performance between different methods.

Keywords: Cryo-Electron Tomogram, macromolecular
crowding, intercelluar simulation, SARS-CoV-2 simulation