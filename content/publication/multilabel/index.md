---
title: "Learning Deep Latent Space for Multi-Label Classification"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chih-Kuan Yeh
- Wei-Chieh Wu
- Wei-Jen Ko
- Yu-Chiang Frank Wang


# Author notes (optional)
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2017"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-2-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In  AAAI Conference on Artificial Intelligence 2017
publication_short: In AAAI 2017

abstract: Multi-label classification is a practical yet challenging task in machine learning related fields, since it requires the prediction of more than one label category for each input instance. We propose a novel deep neural networks (DNN) based model, Canonical Correlated AutoEncoder (C2AE), for solving this task. Aiming at better relating feature and label domain data for improved classification, we uniquely perform joint feature and label embedding by deriving a deep latent space, followed by the introduction of label-correlation sensitive loss function for recovering the predicted label outputs. Our C2AE is achieved by integrating the DNN architectures of canonical correlation analysis and autoencoder, which allows end-to-end learning and prediction with the ability to exploit label dependency. Moreover, our C2AE can be easily extended to address the learning problem with missing labels. Our experiments on multiple datasets with different scales confirm the effectiveness and robustness of our proposed method, which is shown to perform favorably against state-of-the-art methods for multi-label classification.


# Summary. An optional shortened abstract.
summary: A multi-label algorithm with a deep Canonical Correlated AutoEncoder structure.

tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
#links:
# - name: Blog
#   url: https://blog.ml.cmu.edu/2019/04/19/representer-point-selection-explain-dnn/

url_pdf: 'https://arxiv.org/pdf/1707.00418.pdf'
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
