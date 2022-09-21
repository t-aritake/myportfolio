---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Single-molecule localization by voxel-wise regression using convolutional neural network"
authors: ["Toshimitsu Aritake", "Hideitsu Hino", "Shigeyuki Namiki", "Daisuke Asanuma", "Kenzo Hirose", "Noboru Murata"]
date: 2020-11-01
doi: "10.1016/j.rio.2020.100019"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-14T20:02:21+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Results in Optics"
publication_short: ""

abstract: "Single-molecule localization microscopy is widely used in biological research for measuring the nanostructures of samples smaller than the diffraction limit. In this paper, a novel method for regression of the coordinates of molecules for multifocal plane microscopy is presented. A regression problem for the target space is decomposed into regression problems for small subsets of the target space. Then, a deep neural network is used to solve these problems. By decomposing the regression problem, a fully convolutional neural network can be used to solve the regression problems. The computation of the network is efficient, and a simple and parameter-free loss function can be used to train the network. The proposed algorithm is validated by both simulated and real data obtained by quad-plane microscopy."

# Summary. An optional shortened abstract.
summary: ""

tags: ['sparse modeling', 'microscopy']
categories: []
featured: true

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
