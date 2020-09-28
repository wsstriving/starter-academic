---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "On the Usage of Phonetic Information for Text-independent Speaker Embedding Extraction"
authors: [Shuai Wang, Johan Rohdin, Lukáš Burget, Oldřich Plchot, Yanmin Qian, Kai Yu]
date: 2019-06-25T22:38:51+08:00
doi: "10.21437/Interspeech.2019-3036"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-25T22:38:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "In 20th Annual Conference of the International Speech Communication Association (InterSpeech), Graz, Austria, 2019"
publication_short: "Interspeech 2019"

abstract: "Embeddings extracted by deep neural networks have become the state-of-the-art utterance representation in speaker recognition systems. It has recently been shown that incorporating frame-level phonetic information in the embedding extractor can improve the speaker recognition performance. On the other hand, in the final embedding, phonetic information is just an additional source of session variability which may be harmful to the text-independent speaker recognition task. This suggests that at the embedding level phonetic information should be suppressed rather than encouraged. To verify this hypothesis, we perform several experiments that encourage or/and suppress phonetic information at various stages in the network. Our experiments confirm that multitask learning is beneficial if it is applied at the frame-level stage of the network, whereas adversarial training is beneficial if it is used at the segment-level stage of the network. Additionally, the combination of these two approaches improves the performance further, resulting in an equal error rate of 3.17% on the VoxCeleb dataset."

# Summary. An optional shortened abstract.
summary: "We proposed the segment-level representation for phonetic information and the corresponding segment-level multi-task/adversarial training framework, we revisited the usage the phonetic information for the text-independent embedding learning and designed experiments to verify the assumption: For TI-SV, it could be benificial to remove the phonetic variation in the final speaker embeddings"

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

url_pdf: https://www.isca-speech.org/archive/Interspeech_2019/pdfs/3036.pdf
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
