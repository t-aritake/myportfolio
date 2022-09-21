---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "変数の拡張に対する最適輸送を用いたドメイン適応"
authors: ["有竹 俊光", "日野 英逸"]
date: 2022-01-18
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2022-09-16T23:24:53+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["4"]

# Publication name and optional abbreviated publication name.
publication: "情報論的学習理論と機械学習研究会 (IBISML)"
publication_short: ""

abstract: "ドメイン適応はソースドメインから得られたラベル付きデータに関する知識をターゲットドメイン転移し， ドメイン間での違いを考慮した学習を行うことを目的としている.多くのドメイン適応の方法はソース，ターゲット ドメインが同じ次元であることを仮定している.特にターゲットドメインから得られるテストデータに対してラベル 情報が与えられない場合，各ドメインで変数の数が異なる場合に利用可能な方法の研究は限定的である.本稿では， ソース，ターゲットドメインに共通の変数が存在し，ターゲットドメインでは新たな変数が観測されると仮定し，ター ゲットドメインの変数の数がソースドメインより多くな場合を考える.そして，ソース，ターゲットドメイン間で変 数が共通となる性質を利用し，ドメイン間の適応を最適輸送問題として定式化し，ドメイン適応のアルゴリズムを提 案する.また，提案した最適輸送にもとづくアルゴリズムのターゲット領域における汎化誤差の上界を導出し，提案 法の有効性を人工データおよび実データによって評価する."

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
url_slides: 'slide.pdf'
url_source: 'https://ken.ieice.org/ken/paper/20220118cC7o/'
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
