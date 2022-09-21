---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Unsupervised Domain Adaptation for Extra Features in the Target Domain Using Optimal Transport"
authors: ["Toshimitsu Aritake", "Hideitsu Hino"]
date: 2022-09-13
doi: "10.48550/ARXIV.2209.04594"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-16T23:22:21+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
publication_short: ""

abstract: "Domain adaptation aims to transfer knowledge of labeled instances obtained from a source domain to a target domain to fill the gap between the domains. Most domain adaptation methods assume that the source and target domains have the same dimensionality. Methods that are applicable when the number of features is different in each domain have rarely been studied, especially when no label information is given for the test data obtained from the target domain. In this paper, it is assumed that common features exist in both domains and that extra (new additional) features are observed in the target domain; hence, the dimensionality of the target domain is higher than that of the source domain. To leverage the homogeneity of the common features, the adaptation between these source and target domains is formulated as an optimal transport (OT) problem. In addition, a learning bound in the target domain for the proposed OT-based method is derived. The proposed algorithm is validated using both simulated and real-world data."

# Summary. An optional shortened abstract.
summary: ""

tags: ['domain adaptation']
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
