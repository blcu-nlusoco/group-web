---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "自然语言显式命题识别和解析方法"
authors: [刘璐,彭诗雅,玉郴,于东]
date: 2019-03-27T16:37:18+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-03-27T16:37:18+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "中文信息学报"
publication_short: ""

abstract: "自然语言中包含很多显式命题,正确理解这些命题是理解文本信息的关键。正确识别显式命题并解析其中的关键成分有助于理清语言中的逻辑关系、辅助自然语言理解。该文基于百度百科数据构建了自然语言显式命 题标注数据集,并提出两个研究任务:自然语言显式命题自动识别和命题关键成分解析。其中,显式命题自动识别任务判断一个自然语言句子是否为命题;显式命题关键成分解析任务从已获取的命题中解析出支撑该命题成立的 关键成分。针对任务一,构建基于BERT的二分类模型;针对任务二,构建基于BERT-BiLSTM-CRF的序列标注模型。实验结果表明,模型在任务一的正确率达到74.95%,超过基线模型15.30%;在任务二的F 值达到90.74%, 超过基线模型17.69%。该文为下一步研究提供了可靠的标注数据集和基线方法。"

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

url_pdf: http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=3085
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
