---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Optimizing Bayesian HMM based x-vector clustering for the second DIHARD speech diarization challenge"
authors: [Mireia Diez, Lukáš Burget, Federico Landini, Shuai Wang, Honza Černocký]
date: 2020-06-25T21:45:57+08:00
doi: "10.1109/ICASSP40776.2020.9053982"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T21:45:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Barcelona, Spain, 2020"
publication_short: "ICASSP 2020"

abstract: "This paper presents an analysis of our diarization system winning the second DIHARD speech diarization challenge, track 1. This system is based on clustering x-vector speaker embeddings extracted every 0.25s from short segments of the input recording. In this paper, we focus on the two x-vector clustering methods employed, namely Agglomerative Hierarchical Clustering followed by a clustering based on Bayesian Hidden Markov Model (BHMM). Even though the system submitted to the challenge had further post-processing steps, we will show that using this BHMM solely is enough to achieve the best performance in the challenge. The analysis will show improvements achieved by optimizing individual processing steps, including a simple procedure to effectively perform domain adaptation by Probabilistic Linear Discriminant Analysis model interpolation. All experiments are performed in the DIHARD II evaluation framework."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: [diarization]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: http://www.fit.vutbr.cz/research/groups/speech/publi/2020/diez_icassp2020_09053982.pdf
url_code: https://github.com/BUTSpeechFIT/VBx
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
