---
title: "Data refinement for fully unsupervised visual inspection using pre-trained networks"
authors:
- Antoine Cordier
- admin
- Pierre Gutierrez
date: "2022-02-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Anomaly detection has recently seen great progress in the field of visual inspection. More specifically, the use of classical outlier detection techniques on features extracted by deep pre-trained neural networks have been shown to deliver remarkable performances on the MVTec Anomaly Detection (MVTec AD) dataset. However, like most other anomaly detection strategies, these pre-trained methods assume all training data to be normal. As a consequence, they cannot be considered as fully unsupervised. There exists to our knowledge no work studying these pre-trained methods under fully unsupervised setting. In this work, we first assess the robustness of these pre-trained methods to fully unsupervised context, using polluted training sets (i.e. containing defective samples), and show that these methods are more robust to pollution compared to methods such as CutPaste. We then propose SROC, a Simple Refinement strategy for One Class classification. SROC enables to remove most of the polluted images from the training set, and to recover some of the lost AUC. We further show that our simple heuristic competes with, and even outperforms much more complex strategies from the existing literature.

# Summary. An optional shortened abstract.
summary: 

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

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
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

<!-- Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
