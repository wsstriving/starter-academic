---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Data Augmentation using Deep Generative Models for Embedding based Speaker Recognition"
authors: [Shuai Wang, Yexin Yang, Zhanghao Wu, Yanmin Qian, Kai Yu]
date: 2020-07-30T22:46:42+08:00
doi: "10.1109/TASLP.2020.3016498"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-07-30T22:46:42+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 28, pp. 2598-2609, Nov. 2020"
publication_short: "TASLP 2020"

abstract: "Data augmentation is an effective method to improve the robustness of embedding based speaker verification systems, which could be applied to either the front-end speaker embedding extractor or the back-end PLDA. Different from the conventional augmentation methods such as manually adding noise or reverberation to the original audios, in this article, we propose to use deep generative models to directly generate more diverse speaker embeddings, which would be used for robust PLDA training. Conditional GAN, and VAE are designed, and investigated for different embedding types, including factor analysis based i-vector, TDNN based x-vector, and ResNet based r-vector. The proposed back-end augmentation methods are evaluated on NIST SRE 2016, and 2018 dataset. Within the popular x-vector, and r-vector framework, the experimental results show that our proposed methods can outperform the traditional audio based back-end augmentation method while different front-end augmentation methods are considered."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: [SEL]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://www.dlc.sjtu.edu.cn/en/papers/2020/sw121-wang-taslp20.pdf
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
