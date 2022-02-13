---
title: "Threading the needle for off-manifold and on-manifold value functions for Shapley Value Explanations"
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Chih-Kuan Yeh
- Kuan-Yun Lee
- Frederick Liu
- Pradeep Ravikumar


# Author notes (optional)
author_notes:
- 

date: "2022"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: To Appear In International Conference on Artificial Intelligence and Statistics 2022
publication_short: To Appear In AISTATS 2022

abstract:  A popular explainable AI (XAI) approach to quantify feature importance of a given model is via Shapley values. These Shapley values arose in cooperative games, and hence a critical ingredient to compute these in an XAI context is a so-called value function, that computes the value of a subset of features, and which connects machine learning models to cooperative games.  There are many possible choices for such value functions, which broadly fall into two categories -- on-manifold and off-manifold value functions, which take an observational and an interventional viewpoint respectively. Both these classes however have their respective flaws, as shown in a line of recent work -- on-manifold value functions pay less heed to the model in deference to the underlying data distribution, violate key axiomatic properties, and are computationally expensive; while off-manifold value functions pays less heed to the data manifold, evaluate the model on regions for which it wasn't trained, and are susceptible to adversarial manipulations of the explanations. Thus there is no consensus on which class of value functions to use, and indeed some have argued to ``pick one's poison'' depending on the application at hand. In this paper, we show that in addition to these existing issues, both classes of value functions are prone to adversarial manipulations on low density regions. We formalize the desiderata of value functions that respect both the model as well as the data manifold in a set of axioms and be robust to perturbation on off-manifold regions, and show that there exists a unique value function that satisfies these axioms, which we term the Joint Baseline value function, and the resulting Shapley value the Joint Baseline Shapley (JBshap). We show moreover that JBshap is much more computationally efficient than on-manifold Shapley values, and can be scaled up to high dimensional data such as images.
# Summary. An optional shortened abstract.
summary: A new value function that addresses issues of on-manifold and off-manifold value functions to be used with Shapley value.
tags: []

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)


url_pdf: '' #'https://arxiv.org/pdf/2006.00442.pdf'
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
