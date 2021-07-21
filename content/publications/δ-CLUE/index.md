---
title: "δ-CLUE: Diverse Sets of Explanations for Uncertainty Estimates"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Umang Bhatt
- Adrian Weller

# Author notes (optional)
author_notes:
- "First author"

date: "2021-04-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-07-17T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *ICLR Workshop on Security and Safety in Machine Learning Systems*
publication_short: In *ICLR Workshop on Security and Safety in Machine Learning Systems*

abstract: To interpret uncertainty estimates from differentiable probabilistic models, recent work has proposed generating Counterfactual Latent Uncertainty Explanations (CLUEs). However, for a single input, such approaches could output a variety of explanations due to the lack of constraints placed on the explanation. Here we augment the original CLUE approach, to provide what we call δ-CLUE. CLUE indicates one way to change an input, while remaining on the data manifold, such that the model becomes more confident about its prediction. We instead return a set of plausible CLUEs- multiple, diverse inputs that are within a δ ball of the original input in latent space, all yielding confident predictions.

# Summary. An optional shortened abstract.
summary: To interpret uncertainty estimates, we extend recent work that generates Counterfactual Latent Uncertainty Explanations (CLUEs), to produce a set of plausible CLUEs- multiple, diverse inputs that are within a δ ball of the original input in latent space, all yielding confident predictions. 

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2104.06323.pdf'
url_code: ''
url_dataset: ''
url_poster: '../../posters/δ-CLUE-Poster.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

To interpret uncertainty estimates from differentiable probabilistic models, recent work has proposed generating Counterfactual Latent Uncertainty Explanations (CLUEs). However, for a single input, such approaches could output a variety of explanations due to the lack of constraints placed on the explanation. Here we augment the original CLUE approach, to provide what we call δ-CLUE. CLUE indicates one way to change an input, while remaining on the data manifold, such that the model becomes more confident about its prediction. We instead return a set of plausible CLUEs: multiple, diverse inputs that are within a δ ball of the original input in latent space, all yielding confident predictions.
