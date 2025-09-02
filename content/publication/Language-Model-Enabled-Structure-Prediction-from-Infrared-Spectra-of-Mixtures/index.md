---
title: "Language Model Enabled Structure Prediction from Infrared Spectra of Mixtures"
authors:
  - admin
  - Marvin Alberts
  - Teodoro Laino
  
author_notes:
  - Work dony while interning at IBM Research Zürich
  - IBM Research Zürich
  - IBM Research Zürich
  
date: "2025-07-02T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-02T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Transformer language models recently enabled molecular structure prediction directly from infrared (IR) spectra, yet have remained confined to pure compounds. We show that the same architecture learns the correlations embedded in binary mixture spectra and can retrieve the individual molecular components. Trained solely on gas-phase data, our model attains a Top-10 accuracy of 61.4% on balanced synthetic mixtures. When evaluated on 15 mixtures measured with Attenuated Total Reflectance (ATR) IR spectrometer, whose response differs markedly from the training domain, it still achieves 52.0% Top-10 accuracy, evidencing strong cross-instrument transferability. The ability to identify signals of individual molecules within complex spectra extends machine-learning-assisted spectroscopy from idealised samples to realistic laboratory scenarios. All code and pretrained weights are released to accelerate adoption and further development. This advance opens the door to automated structure elucidation using IR data in fields ranging from environmental monitoring to pharmaceutical quality control.

# Summary. An optional shortened abstract.
summary: 

tags:
- Large Language Models
- AI for Chemistry

featured: true

hugoblox:
  ids:
    doi: https://doi.org/10.26434/chemrxiv-2025-vl4ng

links:
- type: pdf
  url: https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/686249a91a8f9bdab5bfefee/original/language-model-enabled-structure-prediction-from-infrared-spectra-of-mixtures.pdf
- type: code
  url: https://github.com/rxn4chemistry/MultimodalAnalytical
- type: dataset
  url: https://zenodo.org/records/14770232

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image taken from github.com/rxn4chemistry/MultimodalAnalytical/'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- 

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
