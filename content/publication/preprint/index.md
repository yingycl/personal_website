---
title: "A multiobjective evolutionary approach for solving large-scale network reconstruction problems via logistic principal component analysis"
authors:
- admin
- Jing Liu
- Kai Wu
- Chao Wang
date: "2021-07-20"
doi: "10.36227/techrxiv.15022701"

# Schedule page publish date (NOT publication's date).
publishDate: "2020"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "TechRxiv"
publication_short: ""

abstract: Currently, the problem of uncovering complex network structure and dynamics from time series is prominent in many fields. Despite the recent progress in this area, reconstructing large-scale networks from limited data remains a tough problem. Existing works treat connections of nodes as continuous values, leaving a challenge of setting a proper cut-off value to distinguish whether the connections exist or not. Besides, their performances on large-scale networks are far from satisfactory. Considering the reconstruction error and sparsity as two objectives, this paper proposes a subspace learning based evolutionary multiobjective network reconstruction algorithm, termed as SLEMO-NR, to solve the aforementioned problems. In the evolutionary process, we assume that binary-coded individuals obey the Bernoulli distribution and can use the probability and natural parameter as the alternative representations. Moreover, our approach utilizes the logistic principal component analysis (LPCA) to learn a subspace containing the features of network structure. The offspring solutions are generated in the learned subspace and then can be mapped back to the original space via LPCA. Benefitting from the alternative representations, a preference-based local search operator is proposed to concentrate on finding solutions approximate to the true sparsity. The experimental results on synthetic networks and six real-world networks demonstrate that, due to the well-learned network structure subspace and the preference-based strategy, our approach is effective in reconstructing large-scale networks compared to six existing methods.

# Summary. An optional shortened abstract.
summary: This paper proposes a subspace learning based evolutionary multiobjective algorithm to sovle large-scale network reconstruction problems.

tags:
#- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: http://
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
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


#{{% alert note %}}
#Click the *Slides* button above to demo Academic's Markdown #slides feature.
#{{% /alert %}}

#Supplementary notes can be added here, including [code and math]
#(https://sourcethemes.com/academic/docs/writing-markdown-latex/).
---