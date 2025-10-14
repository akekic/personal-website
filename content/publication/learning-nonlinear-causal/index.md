---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Learning Nonlinear Causal Reductions to Explain Reinforcement Learning Policies"
authors: 
  - admin
  - Jan Schneider
  - Dieter Büchler
  - Bernhard Schölkopf
  - Michele Besserve

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 'Shared last author'
  - 'Shared last author'

date: 2025-07-21T12:00:00+01:00
doi:

# Schedule page publish date (NOT publication's date).
publishDate: 2025-07-23T12:00:00+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: "arXiv"

abstract: "Why do reinforcement learning (RL) policies fail or succeed? This is a challenging question due to the complex, high-dimensional nature of agent-environment interactions. In this work, we take a causal perspective on explaining the behavior of RL policies by viewing the states, actions, and rewards as variables in a low-level causal model. We introduce random perturbations to policy actions during execution and observe their effects on the cumulative reward, learning a simplified high-level causal model that explains these relationships. To this end, we develop a nonlinear Causal Model Reduction framework that ensures approximate interventional consistency, meaning the simplified high-level model responds to interventions in a similar way as the original complex system. We prove that for a class of nonlinear causal models, there exists a unique solution that achieves exact interventional consistency, ensuring learned explanations reflect meaningful causal patterns. Experiments on both synthetic causal models and practical RL tasks-including pendulum control and robot table tennis-demonstrate that our approach can uncover important behavioral patterns, biases, and failure modes in trained RL policies."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
# - name: Thread
#   url: https://x.com/armin_kekic/status/1801544498071097385
#   icon_pack: fab
#   icon: twitter
- name: arXiv
  url: https://arxiv.org/abs/2507.14901
  icon_pack: ai
  icon: arxiv

url_pdf: "https://arxiv.org/pdf/2507.14901"
url_code:
url_dataset:
url_poster: "https://drive.google.com/file/d/1bgAfH8_Zt1g1uo5WnlM2kTQkbBIT3pPy/view?usp=sharing"
url_project:
url_slides: "https://drive.google.com/file/d/1T9R3bvFmnGBxlCj61PyJCfM9R8yGziIz/view?usp=sharing"
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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
