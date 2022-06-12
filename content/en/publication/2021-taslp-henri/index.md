---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Voice activity detection in the wild: A data-driven approach using teacher-student training"
authors: [Heinrich Dinkel, Shuai Wang, Xuenan Xu, Mengyue Wu, Kai Yu]
date: 2021-06-13T22:06:00+08:00
doi: "10.1109/TASLP.2021.3073596"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-06-13T22:06:00+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/ACM Transactions on Audio, Speech, and Language Processing, vol. 29, pp. 1542-1555, Nov. 2021"
publication_short: "TASLP 2021"

abstract: "Voice activity detection is an essential pre-processing component for speech-related tasks such as automatic speech recognition (ASR). Traditional supervised VAD systems obtain frame-level labels from an ASR pipeline by using, e.g., a Hidden Markov model. These ASR models are commonly trained on clean and fully transcribed data, limiting VAD systems to be trained on clean or synthetically noised datasets. Therefore, a major challenge for supervised VAD systems is their generalization towards noisy, real-world data. This work proposes a data-driven teacher-student approach for VAD, which utilizes vast and unconstrained audio data for training. Unlike previous approaches, only weak labels during teacher training are required, enabling the utilization of any real-world, potentially noisy dataset. Our approach firstly trains a teacher model on a source dataset (Audioset) using clip-level supervision. After training, the teacher provides frame-level guidance to a student model on an unlabeled, target dataset. A multitude of student models trained on mid- to large-sized datasets are investigated (Audioset, Voxceleb, NIST SRE). Our approach is then respectively evaluated on clean, artificially noised, and real-world data. We observe significant performance gains in artificially noised and real-world scenarios. Lastly, we compare our approach against other unsupervised and supervised VAD methods, demonstrating our method’s superiority."

# Summary. An optional shortened abstract.
summary: "Leaveraging weak-labeled data for voice activity detection in a teacher-student manner"

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

url_pdf: https://arxiv.org/pdf/2105.04065.pdf
url_code: https://github.com/RicherMans/Datadriven-GPVAD
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
