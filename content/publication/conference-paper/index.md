---
title: "IDEA: a web server for Interactive Differential Expression Analysis with R Packages"
authors:
- admin
- Yubin Xie
- Peng Nie
- Rucheng Diao
- Licheng Sun
- Zhixiang Zuo
- Jian Ren
date: "2018-07-01T00:00:00Z"
doi: "https://doi.org/10.1101/360461"

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *bioRxiv*
publication_short: In *bioRxiv*

abstract: Differential expression (DE) analysis is a fundamental task in the downstream analysis of the next-generation sequencing (NGS) data. Up to now, a number of R packages have been developed for detecting differentially expressed genes. Although R language has an interaction-oriented programming design, for many biology researchers, a lack of basic programming skills has greatly hindered the application of these R packages. To address this issue, we developed the Interactive Differential Expression Analyzer (IDEA), a Shiny-based web application integrating the differential expression analysis related R packages into a graphical user interface (GUI), allowing users to run the analysis without writing any new code. A wide variety of charts and tables are generated to facilitate the interpretation of the results. In addition, IDEA also provides a combined analysis framework which helps to reconcile any discrepancy from different computational methods. As a public data analysis server, IDAE is implemented in HTML, CSS and JavaScript, and is freely available at http://idea.renlab.org.

# Summary. An optional shortened abstract.
summary: IDEA was built as a user-friendly and highly interactive utility using the Shiny (RStudio Inc. 2014) package in R. Currently, five relevant R packages are integrated into IDEA. IDEA is capable of visualizing the results with plenty of charts and tables, as well as providing great ease of interaction during the course of the analysis.

tags:
- Source Themes
featured: false

links:
- name: Custom Link
  url: https://likelet.github.io/publication/zhao2018idea/
url_pdf: ''
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides:
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
