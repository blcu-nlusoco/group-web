---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Token Level Adaptive Training for Neural Machine Translation"
authors: [谷舒豪, Jinchao Zhang, Fandong Meng, 冯洋, 谢婉莹, Jie Zhou, 于东]
date: 2020-11-16T09:25:27+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-29T09:25:27+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing"
publication_short: ""

abstract: "There exists a token imbalance phenomenon in natural language as different tokens appear with different frequencies, which leads to different learning difficulties for tokens in Neural Machine Translation (NMT). The vanilla NMT model usually adopts trivial equal-weighted objectives for target tokens with different frequencies and tends to generate more high-frequency tokens and less low-frequency tokens compared with the golden token distribution. However, low-frequency tokens may carry critical semantic information that will affect the translation quality once they are neglected. In this paper, we explored target token-level adaptive objectives based on token frequencies to assign appropriate weights for each target token during training. We aimed that those meaningful but relatively low-frequency words could be assigned with larger weights in objectives to encourage the model to pay more attention to these tokens. Our method yields consistent improvements in translation quality on ZH-EN, EN-RO, and EN-DE translation tasks, especially on sentences that contain more low-frequency tokens where we can get 1.68, 1.02, and 0.52 BLEU increases compared with baseline, respectively. Further analyses show that our method can also improve the lexical diversity of translation."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.aclweb.org/anthology/2020.emnlp-main.76.pdf
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
