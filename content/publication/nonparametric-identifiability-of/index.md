---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Nonparametric Identifiability of Causal Representations from Unknown Interventions"
authors: 
  - Julius von Kügelgen
  - Michel Besserve
  - Wendong Liang
  - Luigi Gresele
  - admin
  - Elias Bareinboim
  - David M. Blei
  - Bernhard Schölkopf

# Author notes (optional)
author_notes:
  -

date: 2023-09-21T11:00:00+01:00
doi: "https://doi.org/10.48550/arXiv.2306.00542"

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-01T00:01:22+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Conference on Neural Information Processing Systems "
publication_short: "NeurIPS"

abstract: 'We study causal representation learning, the task of inferring latent causal variables and their causal relations from high-dimensional functions ("mixtures") of the variables. Prior work relies on weak supervision, in the form of counterfactual pre- and post-intervention views or temporal structure; places restrictive assumptions, such as linearity, on the mixing function or latent causal model; or requires partial knowledge of the generative process, such as the causal graph or the intervention targets. We instead consider the general setting in which both the causal model and the mixing function are nonparametric. The learning signal takes the form of multiple datasets, or environments, arising from unknown interventions in the underlying causal model. Our goal is to identify both the ground truth latents and their causal graph up to a set of ambiguities which we show to be irresolvable from interventional data. We study the fundamental setting of two causal variables and prove that the observational distribution and one perfect intervention per node suffice for identifiability, subject to a genericity condition. This condition rules out spurious solutions that involve fine-tuning of the intervened and observational distributions, mirroring similar conditions for nonlinear cause-effect inference. For an arbitrary number of variables, we show that two distinct paired perfect interventions per node guarantee identifiability. Further, we demonstrate that the strengths of causal influences among the latent variables are preserved by all equivalent solutions, rendering the inferred representation appropriate for drawing causal conclusions from new data. Our study provides the first identifiability results for the general nonparametric setting with unknown interventions, and elucidates what is possible and impossible for causal representation learning without more direct supervision.'

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
- name: arXiv
  url: https://arxiv.org/abs/2306.00542
  icon_pack: ai
  icon: arxiv
- name: Thread
  url: https://x.com/JKugelgen/status/1733870399568392201?s=20
  icon_pack: fab
  icon: twitter

url_pdf: "https://openreview.net/pdf?id=V87gZeSOL4"
url_code: "https://github.com/akekic/causal-component-analysis"
url_dataset:
url_poster: "https://drive.google.com/file/d/1P6e8OpnmeFZ5RbmWPEuLZpgVYWn27Dba/view?usp=sharing"
url_project:
url_slides:
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
