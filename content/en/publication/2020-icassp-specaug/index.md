---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Investigation of Specaugment for Deep Speaker Embedding Learning"
authors: [Shuai Wang, Johan Rohdin, Oldřich Plchot, Lukáš Burget, Kai Yu, Jan Černocký]
date: 2020-06-25T21:45:36+08:00
doi: "10.1109/ICASSP40776.2020.9053481"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T21:45:36+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Barcelona, Spain, 2020"
publication_short: "ICASSP 2020"

abstract: "SpecAugment is a newly proposed data augmentation method for speech recognition. By randomly masking bands in the log Mel spectogram this method leads to impressive performance improvements. In this paper, we investigate the usage of SpecAugment for speaker verification tasks. Two different models, namely 1-D convolutional TDNN and 2-D convolutional ResNet34, trained with either Softmax or AAM-Softmax loss, are used to analyze SpecAugment’s effectiveness. Experiments are carried out on the Voxceleb and NIST SRE 2016 dataset. By applying SpecAugment to the original clean data in an on-the-fly manner without complex off-line data augmentation methods, we obtained 3.72% and 11.49% EER for NIST SRE 2016 Cantonese and Tagalog, respectively. For Voxceleb1 evaluation set, we obtained 1.47% EER."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: [sid]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://www.researchgate.net/publication/341084451_Investigation_of_Specaugment_for_Deep_Speaker_Embedding_Learning
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
