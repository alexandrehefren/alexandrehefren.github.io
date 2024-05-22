---
title: "Projects"
layout:  single  #collection  single
permalink: /projects/
collection: projects
# entries_layout: grid
classes: wide
toc: false
toc_label: "My Table of Contents"
toc_icon: "cog"
author_profile: false
# sidebar:
  # title: "Sample Title"
  # nav: sidebar-sample #sidebar-projects #
date: 01/12/2023
header:
  # overlay_color: "#333"  #instead of an image only
  overlay_filter: "0.2"
                  #linear-gradient(rgba(70, 130, 180, 0.5), rgba(255, 165, 0, 0.5))
                 #linear-gradient(rgba(0, 0, 0, 0.5), rgba(255, 255, 255, 0.1)) 
                   #linear-gradient(rgba(30, 144, 255, 0.5), rgba(255, 140, 0, 0.5))
                    #linear-gradient(rgba(70, 130, 180, 0.5), rgba(255, 165, 0, 0.5))
                     #Ex: 0.2, rgba(255, 0, 0, 0.5)
  overlay_image: images/photos/DSC_5471-4.jpg
  # og_image:
  # actions:
  #   - label: ""
  #     url: ""
  caption: "Alexandre Hefren"
excerpt: "Practical analyses addressing a variety of problems or questions, illustrating a selection of my interests"
# intro: 
  # - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'


feature_row0:
  - image_path: /images/posts/silkprotein-project/silkprotein.png
    alt: "Silk protein sequences"
    title: "Silk Protein Physics"
    excerpt: Protein chains are analysed accordingly to the number of connections to other polymer chains and their positions along the chain. A node that is able to connect to other sequences is called a "sticker" and is represented by "1", otherwise the node is represented by "0", or an empty circle. How does the specific work to stretch a chain depend on the number of stickers and their position in the presence of extensional flow? This interdisciplinary project is part of a postdoctoral research on the self-assembly of silk protein.
    url: "https://github.com/Alexandre-Hefren/Silk-protein-polymer3D/blob/main/README.md"
    btn_label: "Code"
    btn_class: "btn--primary"  #btn--warning , btn--info, btn--danger, btn--success , 
    tags: 
        - python 
        - machine learning
        - physics
        - polymer
        - biology
        - synthetic data
feature_row1:
  - image_path: images/posts/londonweather-project/londonweather.png
    alt: "London Weather over the years"
    title: "London Weather"
    excerpt: "Despite living in Manchester, a city notorious for its wet and windy weather, I’ve developed an interest in understanding the dynamics of the weather in the UK. I chose to focus on London due to the availability of detailed public data, using it as a case study for England’s weather. This analysis attempts to make sense of the figures behind a frequent topic of local conversation: the weather."
    url: "https://github.com/Alexandre-Hefren/TimeSeries-weather"
    btn_label: "Code"
    btn_class: "btn--primary"
    # url2: "https://"
    # btn_label2: "Code for"
    # btn_class: "btn--primary"
    tags:
        - python
        - london
        - weather
        - data analysis
        - machine learning
        - data visualisation
        - UK
feature_row2:
  - image_path: images/posts/silkprotein-project/silkprotein.png
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
    tags:
feature_row3:
  - image_path: images/posts/silkprotein-project/silkprotein.png
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/ogimage1.png
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This  some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

---



<!-- To appear. -->




<!-- {% include feature_row id="intro" type="center" %} -->

{% include feature_row id="feature_row0" type="left" %}

{% include feature_row id="feature_row1" type="left" %}

<!-- 
{% include feature_row id="feature_row" type="left" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="left" %}

{% include feature_row id="feature_row4" type="left" %} -->