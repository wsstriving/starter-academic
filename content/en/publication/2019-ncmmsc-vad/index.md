---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "End-to-End Speaker-Dependent Voice Activity Detection"
authors: [Yefei Chen, Shuai Wang, Yanmin Qian and Kai Yu]
date: 2019-06-25T23:20:28+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T23:20:28+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "NCMMSC 2019"
publication_short: "In The 15th National Conference on Man-Machine Speech Communication (NCMMSC2019), Xining, Qinghai, China, 2019."

abstract: "Voice activity detection (VAD) is an essential pre-processing step for tasks such as automatic speech recognition (ASR) and speaker recognition. A basic goal is to remove silent segments within an audio, while a more general VAD system could remove all the irrelevant segments such as noise and even unwanted speech from non-target speakers. We define the task, which only detects the speech from the target speaker, as speaker-dependent voice activity detection (SDVAD). This task is quite common in real applications and usually implemented by performing speaker verification (SV) on audio segments extracted from VAD. In this paper, we propose an end-to-end neural network based approach to address this problem, which explicitly takes the speaker identity into the modeling process. Moreover, inference can be performed in an online fashion, which leads to low system latency. Experiments are carried out on a conversational telephone dataset generated from the Switchboard corpus. Results show that our proposed online approach achieves significantly better performance than the usual VAD/SV system in terms of both frame accuracy and F-score. We also used our previously proposed segment-level metric for a more comprehensive analysis."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: [vad]
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://speechlab.sjtu.edu.cn/papers/2019/yfc07-chen-ncmmsc19.pdf
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
