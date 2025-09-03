---
title: 'A Distributional Perspective on Word Learning in Neural Language Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - "admin"
  - "Ryan Cotterell"
  - "Alex Warstadt"

author_notes:
  - "ETH Zürich"
  - "ETH Zürich"
  - "ETH Zürich, UC San Diego"


date: '2025-04-29T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-29T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Proceedings of the 2025 Conference of the Nations of the Americas Chapter of the Association for Computational Linguistics*
publication_short: In *NAACL 2025*

abstract: Language models (LMs) are increasingly being studied as models of human language learners.Due to the nascency of the field, it is not well-established whether LMs exhibit similar learning dynamics to humans, and there are few direct comparisons between learning trajectories in humans and models.Word learning trajectories for children are relatively well-documented, and recent work has tried to extend these investigations to language models.However, there are no widely agreed-upon metrics for word learning in language models.We take a distributional approach to this problem, defining lexical knowledge in terms of properties of the learned distribution for a target word.We argue that distributional signatures studied in prior work fail to capture key distributional information. Thus, we propose an array of signatures that improve on earlier approaches by capturing knowledge of both where the target word can and cannot occur as well as gradient preferences about the word’s appropriateness.We obtain learning trajectories for a selection of small language models we train from scratch, study the relationship between different distributional signatures, compare how well they align with human word learning trajectories and interpretable lexical features, and address basic methodological questions about estimating these distributional signatures.Our metrics largely capture complementary information, suggesting that it is important not to rely on a single metric.However, across all metrics, language models’ learning trajectories fail to correlate with those of children.

# Summary. An optional shortened abstract.
summary: 

tags:
  - Large Language Models

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/v1/2025.naacl-long.558

# Custom links
links:
  - type: pdf
    url: https://aclanthology.org/2025.naacl-long.558.pdf
  - type: code
    url: https://github.com/FilippoFicarra/word_learning
  - type: dataset
    url: https://drive.google.com/drive/folders/1nrxxOX70R0S91b4Wdu3Ecd2Q1oOz0lKp
  - type: slides
    url: https://docs.google.com/presentation/d/1frm5kIfBZO4lTUKkYnHcMWG3jKndaDI5cMEBpSoAu6s/edit?usp=sharing


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Me at the conference in Albuquerque, NM.'
  focal_point: ''
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

