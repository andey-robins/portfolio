---
title: "Synthesis Augmentation with Genetic Algorithms Poster Session"
authors: ['Andey Robins']
date: "2024-03-13T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-13T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Synthesis Augmentation with Genetic Algorithms"
publication_short: "SAGA"

abstract: The von-Neumann architecture has a bottleneck which limits the speed at which data can be made available for computation. To combat this problem, novel paradigms for computing are being developed. One such paradigm, known as in-memory computing, interleaves computation with the storage of data within the same circuits. MAGIC, or Memristor Aided Logic, is an approach which uses memory circuits which physically perform computation through write operations to memory. Sequencing these operations is a computationally difficult problem which is directly correlated with the cost of solutions using MAGIC based in-memory computation. SAGA models the execution sequences as a topological sorting problem which makes the optimization well-suited for genetic algorithms. We then detail the formation and implementation of these genetic algorithms and evaluate them over a number of open circuit implementations. The memory-footprint needed for evaluating each of these circuits is decreased by up to 52% from existing, greedy-algorithm-based optimization solutions. Over the benchmarks evaluated, these modifications lead to an overall improvement in the efficiency of in-memory circuit evaluation of 128% in the best case and 27.5% on average.

# Summary. An optional shortened abstract.
summary: SAGA develops an extension to in-memory based process synthesis.

tags:
- Source Themes
featured: false

# links:
# - name: ""
# #   url: ""
url_pdf: 'uploads/saga_poster.pdf'
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
  caption: 'Image credit: [**Pixl**](https://pixlr.com)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
This work was presented at the Student Scholar Symposium 2024 at UCF and is currently under consideration for publication at GLSVLSI 2024.
{{% /callout %}}

Use the `pdf` button at the top of the page to view the poster.