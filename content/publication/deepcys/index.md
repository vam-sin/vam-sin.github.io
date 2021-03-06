---
title: "DeepCys: Structure‐based multiple cysteine function prediction method trained on deep neural network: Case study on domains of unknown functions belonging to COX2 domains"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Shubham Bogam
- Himaja Devarakonda
- Shubham Paliwal
- Debashree Bandyopadhyay

# Author notes (optional)
author_notes:
-
-
-
-
- Corresponding Author

date: "2021-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In Proteins Structure, Function, and Bioinformatics
publication_short: In Proteins

abstract: Cysteine (Cys) is the most reactive amino acid participating in a wide range of biological functions. In‐silico predictions complement the experiments to meet the need of functional characterization. Multiple Cys function prediction algorithm is scarce, in contrast to specific function prediction algorithms. Here we present a deep neural network‐based multiple Cys function prediction, available on web‐server (DeepCys) (https://deepcys.herokuapp.com/). DeepCys model was trained and tested on two independent datasets curated from protein crystal structures. This prediction method requires three inputs, namely, PDB identifier (ID), chain ID and residue ID for a given Cys and outputs the probabilities of four cysteine functions, namely, disulphide, metal‐binding, thioether and sulphenylation and predicts the most probable Cys function. The algorithm exploits the local and global protein properties, like, sequence and secondary structure motifs, buried fractions, microenvironments and protein/enzyme class. DeepCys outperformed most of the multiple and specific Cys function algorithms. This method can predict maximum number of cysteine functions. Moreover, for the first time, explicitly predicts thioether function. This tool was used to elucidate the cysteine functions on domains of unknown functions belonging to cytochrome C oxidase subunit‐II like transmembrane domains. Apart from the web‐server, a standalone program is also available on GitHub (https://github.com/vam-sin/deepcys).

# Summary. An optional shortened abstract.
summary: DeepCys is a deep learning based tool which uses sequence and structural features pertaining to a cysteine residue to predict four different post-translational modifications of the amino acid.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Manuscript
  url: https://onlinelibrary.wiley.com/doi/10.1002/prot.26056

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
slides: []
---