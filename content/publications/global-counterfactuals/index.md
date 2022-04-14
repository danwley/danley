---
title: "Global Counterfactual Explanations: Investigations, Implementations and Improvements"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Saumitra Mishra
- Daniele Magazzeni

# Author notes (optional)
author_notes:
- "First author"

date: "2022-04-14T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *ICLR Workshop on Privacy, Accountability, Interpretability, Robustness, Reasoning on Structured Data*
publication_short: In *ICLR Workshop on Privacy, Accountability, Interpretability, Robustness, Reasoning on Structured Data*

abstract: The major shortcoming associated with counterfactual methods is their inability to provide explanations beyond the local or instance-level. While some works touch upon the notion of a global explanation, few provide frameworks that are either reliable or computationally tractable. Meanwhile, practitioners are requesting more efficient and interactive explainability tools. We take this opportunity to investigate existing global methods, with a focus on implementing and improving Actionable Recourse Summaries (AReS), the only known global counterfactual explanation framework for recourse.

# Summary. An optional shortened abstract.
summary: The major shortcoming associated with counterfactual methods is their inability to provide explanations beyond the local or instance-level. While some works touch upon the notion of a global explanation, few provide frameworks that are either reliable or computationally tractable. Meanwhile, practitioners are requesting more efficient and interactive explainability tools. We take this opportunity to investigate existing global methods, with a focus on implementing and improving Actionable Recourse Summaries (AReS), the only known global counterfactual explanation framework for recourse.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=Btbgp0dOWZ9'
url_code: ''
url_dataset: ''
url_poster: '../../posters/Global-Counterfactuals.pdf'
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

Counterfactual explanations have been widely studied in explainability, with a range of application dependent methods emerging in fairness, recourse and model understanding. However, the major shortcoming associated with these methods is their inability to provide explanations beyond the local or instance-level. While some works touch upon the notion of a global explanation, typically suggesting to aggregate masses of local explanations in the hope of ascertaining global properties, few provide frameworks that are either reliable or computationally tractable.
Meanwhile, practitioners are requesting more efficient and interactive explainability tools.
We take this opportunity to investigate existing global methods, with a focus on implementing and improving Actionable Recourse Summaries (AReS), the only known global counterfactual explanation framework for recourse.

Published as a workshop paper at ICLR 2022.
