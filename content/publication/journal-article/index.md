---
title: "Learning large-scale fuzzy cognitive maps using an evolutionary many-task algorithm"
authors:
- Chao Wang
- Jing Liu
- Kai Wu
- Chaolong Ying
date: "2021-05-01"
doi: "https://doi.org/10.1016/j.asoc.2021.107441"

# Schedule page publish date (NOT publication's date).
publishDate: "2021"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Applied Soft Computing"
publication_short: ""

abstract: Fuzzy cognitive maps (FCMs) are a powerful tool for simulating and analyzing complex systems. Many efficient methods based on evolutionary algorithms have been proposed to learn small-scale FCMs. However, large number of function evaluations of those methods make them difficult to cope with large-scale FCM learning problems. To overcome this issue, we propose a random inactivation-based batch many-task evolutionary algorithm, termed as IBMTEA-FCM. Inspired by the probability of knowledge sharing in different tasks, the problem of FCM learning is first modeled as a many-task optimization problem, in which each task represents learning local connections of a node in a single FCM. To ensure the effectiveness of knowledge transfer, all tasks are randomly divided into multiple batches to optimize separately. In this method, an evolutionary many-task framework is employed to overcome the proposed many-task FCM learning problem and we randomly deactivate weighted edges to ensure the sparsity of FCM in the evolutionary process. The performance of IBMTEA-FCM is validated on both synthetic datasets and a practical study of gene regulatory network reconstruction. Compared with existing classical methods, the experimental results show that IBMTEA-FCM can learn large-scale FCMs with higher accuracy and less computational cost..

# Summary. An optional shortened abstract.
summary: This paper proposed a random inactivation-based batch many-task evolutionary algorithm to learn large-scale fuzzy cognitive maps.

tags:
#- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S1568494621003641
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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


#{{% alert note %}}
#Click the *Cite* button above to demo the feature to enable #visitors to import publication metadata into their reference #management software.
#{{% /alert %}}

#{{% alert note %}}
#Click the *Slides* button above to demo Academic's Markdown #slides feature.
#{{% /alert %}}

#Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
---