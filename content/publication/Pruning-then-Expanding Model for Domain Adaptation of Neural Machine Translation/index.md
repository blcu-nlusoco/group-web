---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Pruning Then Expanding Model for Domain Adaptation of Neural Machine Translation"
authors: [谷舒豪, 冯洋, 谢婉莹]
date: 2021-03-29T09:21:50+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-29T09:21:50+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NAACL-2021"
publication_short: ""

abstract: "Domain Adaptation is widely used in practical applications of neural machine translation, which aims to achieve good performance on both the general-domain and in-domain. However, the existing methods for domain adaptation usually suffer from catastrophic forgetting, domain divergence, and model explosion. To address these three problems, we propose a method of divide and conquer which is based on the importance of neurons or parameters in the translation model. In our method, we first prune the model and only keep the important neurons or parameters, making them responsible for both general-domain and in-domain translation. Then we further train the pruned model supervised by the original unpruned model with the knowledge distillation method. Last we expand the model to the original size and fine-tune the added parameters for the in-domain translation. We conduct experiments on different languages and domains and the results show that our method can achieve significant improvements compared with several strong baselines."

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

url_pdf: https://arxiv.org/pdf/2103.13678v1.pdf
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
