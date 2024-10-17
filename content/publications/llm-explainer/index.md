---
title: "In-Context Explainers: Harnessing LLMs for Explaining Black Box Models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Nicholas Kroeger
- admin
- Satyapriya Krishna
- Chirag Agarwal
- Himabindu Lakkaraju

# Author notes (optional)
author_notes:
- "First author"
- "First author"

date: "2024-10-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: Preprint

abstract: ""

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2310.05797'
url_code: ''
url_dataset: ''
url_poster: ''
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

Recent advancements in Large Language Models (LLMs) have demonstrated exceptional capabilities in complex tasks like machine translation, commonsense reasoning, and language understanding. One of the primary reasons for the adaptability of LLMs in such diverse tasks is their in-context learning (ICL) capability, which allows them to perform well on new tasks by simply using a few task samples in the prompt. Despite their effectiveness in enhancing the performance of LLMs on diverse language and tabular tasks, these methods have not been thoroughly explored for their potential to generate post hoc explanations. In this work, we carry out one of the first explorations to analyze the effectiveness of LLMs in explaining other complex predictive models using ICL. To this end, we propose a novel framework, In-Context Explainers, comprising of three novel approaches that exploit the ICL capabilities of LLMs to explain the predictions made by other predictive models. We conduct extensive analysis with these approaches on real-world tabular and text datasets and demonstrate that LLMs are capable of explaining other predictive models similar to state-of-the-art post hoc explainers, opening up promising avenues for future research into LLM-based post hoc explanations of complex predictive models.

Preprint (under review).