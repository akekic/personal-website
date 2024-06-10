---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: PhD Student (Machine Learning and Causality)
    company: Max Planck Institute for Intelligent Systems
    company_url: 'https://is.mpg.de/'
    location: Tübingen, Germany
    date_start: '2021-09-15'
    date_end: ''
    description: |2-
        My main interest lies in developing methods for causal representation learning in realistic scenarios. I am a member of the [Empirical Inference Department](https://ei.is.mpg.de) supervised by [Bernhard Schölkopf](https://ei.is.mpg.de/person/bs).

  - title: Applied Scientist (Algorithmic Pricing)
    company: Zalando SE
    company_url: 'https://engineering.zalando.com/'
    location: Berlin, Germany
    date_start: '2018-02-01'
    date_end: '2021-08-31'
    description: |2-
        At the Pricing and Forecasting Department, our main mission was to develop an automated desicion making system that selects optimal dynamic prices for fashion articles (millions of pricing decisions at each iteration). In particular, I modeled [high-dimensional time series](/publication/deep-learning-based/) using deep learning to predict how price changes affect sales. To make good and reliable decisions in the real world, automated systems have to understand the difference between correlation and causation; this got me intersted in the topic of my PhD.
        
  - title: Researcher (Spectroscopic Networks)
    company: University of Heidelberg
    company_url: 'https://www.physi.uni-heidelberg.de/Forschung/QD/'
    location: Heidelberg, Germany
    date_start: '2017-03-01'
    date_end: '2018-01-31'
    description: We [applied methods from network science to spectroscopic data of atoms](/publication/a-network-approach) and found that we can predict the existence of atomic transitions. Additionally, community structure in spectroscopic networks corresponds to physical properties of the quantum states. This project at the intersection of physics and computer science tried to explore what we can learn about physical systems by purely looking at data science methods, rather than building a microscopic physical model.
---
