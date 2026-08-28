---
title: "Projects"
description: "Hands-on analyses across physics, biology and data — some from my academic research, others built out of curiosity or for fun."
excerpt: "Practical analyses addressing a variety of problems or questions, illustrating a selection of my interests. Some are a small part of larger research projects; others are exploratory, curiosity-driven, or simply for fun"
headerImage: "/images/photos/DSC_5471-4.jpg"
projects:
  # NOTE — current work. Deliberately broad: it covers several single-molecule
  # projects, and will be narrowed to the first one that gets a post/page.
  #   - the title is a placeholder, expected to change
  #   - no repo or project page yet, so only `status` shows
  #   - do NOT link SMFAnalysis.jl: that repo on your account is a FORK of
  #     owensnick/SMFAnalysis.jl, so it is not your project
  #   - check what is shareable before linking unpublished research
  - image_path: "/images/posts/genomics-project/cloudrainplot.png"
    alt: "Raincloud plot of nucleosome repeat length distributions across ChromHMM chromatin states"
    title: "Single-Molecule Genomics"
    excerpt: "Nucleosome repeat length in chromatin states: how does it differ between active promoters, enhancers, heterochromatin and quiescent regions? This and other questions are explored in single-molecule genomics analyses, using ES cell data from the Gene Regulatory Defects in Disease Group at Exeter."
    # status: "Page in preparation"   # previous wording
    status: "Project note"
    # page_url: "/projects/genomics/"        # when a page exists
    # code_url: "https://github.com/…"       # when a repo exists
    tags:
      - genomics
      - chromatin
      - single-molecule
      - bioinformatics
      - python
      - data analysis

  - image_path: "/images/posts/silkprotein-project/silkprotein.png"
    alt: "Silk protein sequences"
    title: "Silk Protein Physics"
    excerpt: "Protein chains are analysed according to the number of connections to other polymer chains and their positions along the chain. A node that is able to connect to other sequences is called a \"sticker\" and is represented by \"1\"; otherwise, the node is represented by \"0\", or an empty circle. How does the specific work to stretch a chain depend on the number of stickers and their positions in the presence of extensional flow? This interdisciplinary project is part of postdoctoral research on the self-assembly of silk protein."
    code_url: "https://github.com/Alexandre-Hefren/Silk-protein-polymer3D/blob/main/README.md"
    tags:
      - python
      - machine learning
      - physics
      - polymer
      - biology
      - synthetic data
  - image_path: "/images/posts/londonweather-project/londonweather.png"
    alt: "London Weather over the years"
    title: "London Weather"
    excerpt: "Living in Manchester, a city notorious for its wet and windy weather, I've developed an interest in understanding the dynamics of UK weather. I chose to focus on London due to the availability of detailed public data, using it as a case study of England's weather. This analysis attempts to make sense of the figures behind a frequent topic of local conversation: the weather."
    code_url: "https://github.com/Alexandre-Hefren/TimeSeries-weather"
    tags:
      - python
      - london
      - weather
      - data analysis
      - machine learning
      - data visualisation
      - UK

  # NOTE: the full project page (content/projects/backflow/index.md) is draft: true.
  # This card advertises the project without linking to it. To publish:
  #   1. remove `draft: true` from content/projects/backflow/index.md
  #   2. move _private/interactive back into static/
  #   3. uncomment `page_url` below and delete `status`
  #
  # Converted from the thesis figure (source PDF: _private/backflow-source/)
  - image_path: "/images/posts/backflow-project/backflow_preview.png"
    alt: "Quantum backflow parameter curves for the jump defect"
    title: "Quantum Backflow"
    # Previous (full) version, restore when the page goes live:
    # excerpt: "A quantum particle with strictly positive momentum can carry a negative probability current — flowing backwards with no classical counterpart. This is the subject of my doctoral thesis at the University of York. The interactive visualisation below shows the backflow parameter β_V(f) for a particle scattering off a jump defect, for several values of the potential strength α."
    excerpt: "A quantum particle with strictly positive momentum can carry a negative probability current — flowing backwards, with no classical counterpart. How does backflow change in the presence of different defects, and in particular the jump defect? This was one of the questions I addressed in my doctoral thesis at the University of York."
    code_url: "https://github.com/Alexandre-Hefren/Backflow_Defects"
    # status: "Page in preparation"   # previous wording
    status: "Project note"
    # page_url: "/projects/backflow/"    # uncomment when the page is published
    tags:
      - physics
      - quantum mechanics
      - fortran
      - computational physics
      - phd
---
