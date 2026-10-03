---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'My Research Interests'
      subtitle: ''
      text: |-
        My research interests focus on improving and understanding Large Language Models (LLMs). 
        I am particularly passionate about model optimization and efficiency, including methods for distributed learning, 
        multi-device setups, and knowledge sharing between models. I am also curious about how LLMs work internally, 
        why they hallucinate, and whether their behavior can be leveraged for new applications. 

        In addition, I am deeply interested in the security and privacy of AI systems, exploring potential vulnerabilities 
        and ways to mitigate them.
    design:
      columns: '1'
  - block: collection
    id: news
    content:
      title: News!
      subtitle: ''
      text: |-
        * **Jul 2026**: 🚀 Excited to share that I have joined **Google** (Zurich) as a **Software Engineer**!
        * **Sep 2025**: 🥳 Thrilled to share that [**Language Model Enabled Structure Prediction**](https://filippoficarra.github.io/publication/language-model-enabled-structure-prediction-from-infrared-spectra-of-mixtures/) was accepted to AI4MAT at **NeurIPS 2025**!
        * **Feb 2025**:  🥳 Thrilled to share that [**A Distributional Perspective on Word Learning in Neural Language Models**](https://filippoficarra.github.io/publication/a-distributional-perspective-on-word-learning-in-neural-language-models/) was accepted to **NAACL 2025**.
      page_type: "compact"
      count: 0
    design:
      # '1' column is best for a list of bullet points
      columns: '1'
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  
---
