---
title: "Automatic Bridge Bidding Using Deep Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chih-Kuan Yeh
- Cheng-Yu Hsieh
- Hsuan-Tien Lin


# Author notes (optional)
author_notes:
-

date: "2018"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-11-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Trasaction of Games 2018
publication_short: In IEEE Trasaction of Games 2018 (shorter version in ECAI 2016)

abstract: Bridge is among the zero-sum games for which artificial intelligence has not yet outperformed expert human players. The main difficulty lies in the bidding phase of bridge, which requires cooperative decision making with partial information. Existing artificial intelligence systems for bridge bidding rely on, and are thus restricted by, human-designed bidding systems or features. In this work, we propose a flexible and pioneering bridge-bidding system, which can learn either with or without the aid of human domain knowledge. The system is based on a novel deep reinforcement learning model, which extracts sophisticated features and learns to bid automatically based on raw card data. The model includes an upper-confidence-bound algorithm and additional techniques to achieve a balance between exploration and exploitation. We further study how different pieces of human knowledge can be exploited to assist the model. Our experiments demonstrate the promising performance of our proposed model. In particular, the model can advance from having no knowledge on bidding to achieving a superior performance compared with a champion-winning computer bridge program that implements a human-designed bidding system. In addition, further synergies can be extracted by incorporating expert knowledge into the proposed model.


# Summary. An optional shortened abstract.
summary: The first automatic bridge bidding system using Deep reinforcement learning.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
#links:

url_pdf: 'https://www.csie.ntu.edu.tw/~htlin/paper/doc/bridgedrl.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.


# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
