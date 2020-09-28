---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Knowledge Distillation for Small Foot-print Deep Speaker Embedding"
authors: [Shuai Wang, Yexin Yang, Tianzhe Wang, Yanmin Qian and Kai Yu]
date: 2019-06-25T23:23:14+08:00
doi: "10.1109/ICASSP.2019.8683443"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T23:23:14+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Brighton, UK, 2019"
publication_short: "ICASSP 2019"

abstract: "Deep speaker embedding learning is an effective method for speaker identity modelling. Very deep models such as ResNet can achieve remarkable results but are usually too computationally expensive for real applications with limited resources. On the other hand, simply reducing model size is likely to result in significant performance degradation. In this paper, label-level and embedding-level knowledge distillation are proposed to narrow down the performance gap between large and small models. Label-level distillation utilizes the posteriors obtained by a well-trained teacher model to guide the opti-mization of the student model, while embedding-level distillation directly constrains the similarity between embeddings learned by two models. Experiments were carried out on the VoxCeleb1 dataset. Results show that the proposed knowledge distillation methods can significantly boost the performance of highly compact student models"

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

url_pdf: https://speechlab.sjtu.edu.cn/papers/2019/sw121-wang-icassp2019.pdf
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
