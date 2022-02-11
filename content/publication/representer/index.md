---
title: "Representer Point Selection for Explaining Deep Neural Networks"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chih-Kuan Yeh
- Joon Sik Kim
- Ian En-Hsu Yen
- Pradeep Ravikumar


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2018"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-12-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In Conference on Neural Information Processing Systems 2018
publication_short: In NeurIPS 2018

abstract: We propose to explain the predictions of a deep neural network, by pointing to the set of what we call representer points in the training set, for a given test point prediction. Specifically, we show that we can decompose the pre-activation prediction of a neural network into a linear combination of activations of training points, with the weights corresponding to what we call representer values, which thus capture the importance of that training point on the learned parameters of the network. But it provides a deeper understanding of the network than simply training point influence, with positive representer values corresponding to excitatory training points, and negative values corresponding to inhibitory points, which as we show provides considerably more insight. Our method is also much more scalable, allowing for real-time feedback in a manner not feasible with influence functions.

# Summary. An optional shortened abstract.
summary: Decompose test point predictions by training data with representer theorem.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
 - name: Blog
   url: https://blog.ml.cmu.edu/2019/04/19/representer-point-selection-explain-dnn/

url_pdf: 'https://arxiv.org/pdf/1811.09720.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_blog: 'https://blog.ml.cmu.edu/2019/04/19/representer-point-selection-explain-dnn/'
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
