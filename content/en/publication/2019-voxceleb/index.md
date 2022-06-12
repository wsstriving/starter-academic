---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "BUT system description to voxceleb speaker recognition challenge 2019"
authors: [Hossein Zeinali, Shuai Wang, Anna Silnova, Pavel Matějka, Oldřich Plchot]
date: 2019-06-26T13:31:19+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-26T13:31:19+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "In this report, we describe the submission of Brno University of Technology (BUT) team to the VoxCeleb Speaker Recognition Challenge (VoxSRC) 2019. We also provide a brief analysis of different systems on VoxCeleb-1 test sets. Submitted systems for both Fixed and Open conditions are a fusion of 4 Convolutional Neural Network (CNN) topologies. The first and second networks have ResNet34 topology and use two-dimensional CNNs. The last two networks are one-dimensional CNN and are based on the x-vector extraction topology. Some of the networks are fine-tuned using additive margin angular softmax. Kaldi FBanks and Kaldi PLPs were used as features. The difference between Fixed and Open systems lies in the used training data and fusion strategy. The best systems for Fixed and Open conditions achieved 1.42% and 1.26% ERR on the challenge evaluation set respectively."

# Summary. An optional shortened abstract.
summary: "This paper describes the winning systems developed by the BUT team for the two tracks of the First VoxSRC Speaker Recognition Challenge"

tags: []
categories: [SEL]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_preprint: https://arxiv.org/pdf/1910.12592.pdf
url_code: https://github.com/wenet-e2e/wespeaker/tree/master/wespeaker
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
