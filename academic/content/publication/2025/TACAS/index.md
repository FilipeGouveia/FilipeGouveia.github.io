---
title: "Proxy Attribute Discovery in Machine Learning Datasets via Inductive Logic Programming"

draft: false

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Rafael Gonçalves
- admin
- Inês Lynce

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2025-05-01T00:00:00Z"
doi: "10.1007/978-3-031-90653-4_17"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1", "Conference paper"]

# Publication name and optional abbreviated publication name.
publication: In *Tools and Algorithms for the Construction and Analysis of Systems *
publication_short: In *TACAS 2025*

abstract: The issue of fairness is a well-known challenge in Machine Learning (ML) that has gained increased importance with the emergence of Large Language Models (LLMs) and generative AI. Algorithmic bias can manifest during the training of ML models due to the presence of sensitive attributes, such as gender or racial identity. One approach to mitigate bias is to avoid making decisions based on these protected attributes. However, indirect discrimination can still occur if sensitive information is inferred from proxy attributes. To prevent this, there is a growing interest in detecting potential proxy attributes before training ML models. In this case study, we report on the use of Inductive Logic Programming (ILP) to discover proxy attributes in training datasets, with a focus on the ML classification problem. While ILP has established applications in program synthesis and data curation, we demonstrate that it can also advance the state of the art in proxy attribute discovery by removing the need for prior domain knowledge. Our evaluation shows that this approach is effective at detecting potential sources of indirect discrimination, having successfully identified proxy attributes in several well-known datasets used in fairness-awareness studies.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Fairness", "Machine Learning", "Proxy Attributes", "Inductive Logic Programming"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: '/publication/2025/tacas/TACAS2025.pdf'
url_code: 'https://doi.org/10.5281/zenodo.14618504'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: '/publication/2025/tacas/slidestacas25.pdf'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- RIGA

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

