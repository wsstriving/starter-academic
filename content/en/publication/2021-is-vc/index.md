---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Non-Parallel Any-to-Many Voice Conversion by Replacing Speaker Statistics"
authors: [Yufei Liu, Chengzhu Yu, Shuai Wang, Zhenchuan Yang, Chao Yang, Weibin Zhang]
date: 2021-09-28T20:42:06+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-09-28T20:42:06+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In 21th Annual Conference of the International Speech Communication Association (InterSpeech), Brno, Czech Republic, 2021"
publication_short: "Interspeech 2021"

abstract: "This paper proposes a non-parallel any-to-many voice conver sion (VC) approach with a novel statistics replacement layer. Non-parallel VC is usually achieved by firstly disentangling linguistic and speaker representations, and then concatenating the linguistic content with the learned target speaker’s embedding at the conversion stage. While such a concatenation-based approach could introduce speaker-specific characteristics into the network, it is not very effective as it entirely relies on the network to learn to combine the linguistic content and the speaker characteristics. Inspired by X-vectors, where the statistics of hidden representation such as means and standard deviations are used for speaker differentiation, we propose a statistics replacement layer in VC systems to directly modify the hidden states to have the target speaker’s statistics. The speaker-specific statistics of hidden states are learned for each target speaker during training and are used as guidance for the statistics replacement layer during inference. Moreover, to better concentrate the speaker information into the statistics of hidden representation, a multitask training with X-vector based speaker classification is also performed. Experimental results with Librispeech and VCTK datasets show that the proposed method can effectively improve the converted speech’s naturalness and similarity." 

# Summary. An optional shortened abstract.
summary: "We introduce the speaker modeling method (statistics based) into the voice conversion"

tags: []
categories: [vc]
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
#   name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://drive.google.com/file/d/1FRaXNO-D_XPo5etH605aaizRA-96Kg7g/view
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
