---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Detecting cell assemblies by NMF-based clustering from calcium imaging data"
authors: ["Mizuo Nagayama", "Toshimitsu Aritake", "Hideitsu Hino", "Takeshi Kanda", "Takehiro Miyazaki", "Masashi Yanagisawa", "Shotaro Akaho", "Noboru Murata"]
date: 2022-05
doi: doi.org/10.1016/j.neunet.2022.01.023

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-19T20:51:11+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Neural Networks"
publication_short: ""

abstract: "A large number of neurons form cell assemblies that process information in the brain. Recent developments in measurement technology, one of which is calcium imaging, have made it possible to study cell assemblies. In this study, we aim to extract cell assemblies from calcium imaging data. We propose a clustering approach based on non-negative matrix factorization (NMF). The proposed approach first obtains a similarity matrix between neurons by NMF and then performs spectral clustering on it. The application of NMF entails the problem of model selection. The number of bases in NMF affects the result considerably, and a suitable selection method is yet to be established. We attempt to resolve this problem by model averaging with a newly defined estimator based on NMF. Experiments on simulated data suggest that the proposed approach is superior to conventional correlation-based clustering methods over a wide range of sampling rates. We also analyzed calcium imaging data of sleeping/waking mice and the results suggest that the size of the cell assembly depends on the degree and spatial extent of slow wave generation in the cerebral cortex."

# Summary. An optional shortened abstract.
summary: ""

tags: ['sparse modeling', 'calcium imaging']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
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
