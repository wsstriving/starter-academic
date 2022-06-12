---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Audio-Visual Deep Neural Network for Robust Person Verification"
authors: [Yanmin Qian, Zhengyang Chen, Shuai Wang]
date: 2021-02-13T22:06:00+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-02-13T22:06:00+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 29, pp. 2079-1092, Nov. 2021"
publication_short: "TASLP 2021"

abstract: "Voice and face are two most popular biometrics for person verification, usually used in speaker verification and face verification tasks. Due to the successful application of deep learning technologies, the single-modal person verification system based on only voice or face has achieved remarkable performance. It has already been observed that individual modality has its own advantage and simply combining these two types of information can lead to a more powerful and robust person verification system. In this work, to fully explore the audiovisual multi-modal learning strategies for person verification, we designed and proposed three types of audio-visual deep neural network (AVN), including feature level AVN (AVN-F), embedding level AVN (AVN-E) and embedding level combination with joint learning AVN (AVN-J). To further enhance the system robustness in real noisy conditions where not both modalities can be accessed with high-quality, we proposed several data augmentation strategies for each proposed AVN: a feature-level multi-modal data augmentation is proposed for AVN-F and an embedding-level data augmentation with novel noise distribution matching is designed for AVN-E. For AVN-J, both the feature and embedding level multi-modal data augmentation methods can be applied. All the proposed models are trained on the VoxCeleb2 dev dataset and evaluated on the standard VoxCeleb1 dataset, and the best system achieves 0.558%, 0.441% and 0.793% EER on the three official trial lists of VoxCeleb1, which is to our knowledge the best published single system results on this corpus for person verification. To validate the robustness of the proposed approaches, a noisy evaluation set based on the VoxCeleb1 is constructed, and experimental results show that the proposed system can significantly boost the system robustness and still show promising performance for person verification under this noisy scenario."

# Summary. An optional shortened abstract.
summary: "An investigation of combining audio and visual information for person identity verification"

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
