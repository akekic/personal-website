---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Causal Component Analysis"
authors: 
  - Wendong Liang
  - admin
  - Julius von Kügelgen
  - Simon Buchholz
  - Michel Besserve
  - Luigi Gresele
  - Bernhard Schölkopf

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
  - 
  - 'Shared last author'
  - 'Shared last author'

date: 2023-09-21T12:00:00+01:00
doi:

# Schedule page publish date (NOT publication's date).
publishDate: 2023-05-30T00:01:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conference on Neural Information Processing Systems "
publication_short: "NeurIPS"

abstract: "Independent Component Analysis (ICA) aims to recover independent latent variables from observed mixtures thereof. Causal Representation Learning (CRL) aims instead to infer causally related (thus often statistically dependent) latent variables, together with the unknown graph encoding their causal relationships. We introduce an intermediate problem termed Causal Component Analysis (CauCA). CauCA can be viewed as a generalization of ICA, modelling the causal dependence among the latent components, and as a special case of CRL. In contrast to CRL, it presupposes knowledge of the causal graph, focusing solely on learning the unmixing function and the causal mechanisms. Any impossibility results regarding the recovery of the ground truth in CauCA also apply for CRL, while possibility results may serve as a stepping stone for extensions to CRL. We characterize CauCA identifiability from multiple datasets generated through different types of interventions on the latent causal variables. As a corollary, this interventional perspective also leads to new identifiability results for nonlinear ICA - a special case of CauCA with an empty graph - requiring strictly fewer datasets than previous results. We introduce a likelihood-based approach using normalizing flows to estimate both the unmixing function and the causal mechanisms, and demonstrate its effectiveness through extensive synthetic experiments in the CauCA and ICA setting."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter
- name: Talk
  url: https://slideslive.com/39011534
  icon_pack: fa
  icon: video
- name: Thread
  url: https://x.com/liang_wendong1/status/1723810209884176566?s=20
  icon_pack: fab
  icon: twitter
- name: arXiv
  url: https://arxiv.org/abs/2305.17225
  icon_pack: ai
  icon: arxiv

url_pdf: "https://openreview.net/pdf?id=HszLRiHyfO"
url_code: "https://github.com/akekic/causal-component-analysis"
url_dataset:
url_poster: "https://drive.google.com/file/d/1V7zenB-PIQ06d5gGqlVgUQ1fSvARpwmP/view?usp=sharing"
url_project:
url_slides: "https://drive.google.com/file/d/12F9HS7mv4Awr-qwCJbW7E50nx1RyYE1O/view?usp=sharing"
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
