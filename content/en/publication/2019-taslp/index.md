---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Discriminative Neural Embedding Learning for Short-Duration Text-Independent Speaker Verification"
authors: [Shuai Wang, Zili Huang, Yanmin Qian, Kai Yu]
date: 2019-06-25T23:56:06+08:00
doi: "10.1109/TASLP.2019.2928128"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T23:56:06+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 27, no. 11, pp. 1686-1696, Nov. 2019"
publication_short: "TASLP 2019"

abstract: "Short duration text-independent speaker verification remains a hot research topic in recent years, and deep neural network based embeddings have shown impressive results in such conditions. Good speaker embeddings require the property of both small intra-class variation and large inter-class difference, which is critical for the ability of discrimination and generalization. Current embedding learning strategies can be grouped into two frameworks: “Cascade embedding learning” with multiple stages and “direct embedding learning” from spectral feature directly. We propose new approaches to achieve more discriminant speaker embeddings. Within the cascade framework, a neural network based deep discriminant analysis (DDA) is proposed to project i-vector to more discriminative embeddings. Within the direct embedding framework, a deep model with more advanced center loss and A-softmax loss is used, the focal loss is also investigated in this framework. Moreover, the traditional i-vector and neural embeddings are finally combined with neural network based DDA to achieve further gain. Main experiments are carried out on a short-duration text-independent speaker verification dataset generated from the SRE corpus. The results show that the newly proposed method is promising for short-duration text-independent speaker verification, and it is consistently better than traditional i-vector and neural embedding baselines. The best embeddings achieve roughly 30% relative EER reduction compared to the i-vector baseline, which could be further enhanced when combined with the i-vector system."

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
