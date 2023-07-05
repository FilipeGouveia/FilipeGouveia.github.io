---
title: "Revision of Boolean Models of Regulatory Networks Using Stable State Observations"

draft: false

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Inês Lynce
- Pedro T. Monteiro

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2020-02-06T00:00:00Z"
doi: "10.1089/cmb.2019.0289"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Journal of Computational Biology*
publication_short: In *JCB*

abstract: Models of biological regulatory networks are essential to understand cellular processes. However, the definition of such models is still mostly manually performed, and consequently prone to error. Moreover, as new experimental data are acquired, models need to be revised and updated. Here, we propose a model revision procedure and associated tool, capable of providing the set of minimal repairs to render a model consistent with a set of experimental observations. We consider four possible repair operations, using a lexicographic optimization criterion, giving preference to function repairs over topological ones. Also, we consider observations at stable state discarding the model dynamics. In this article, we extend our previous work to tackle the problem of repairing nodes with multiple reasons of inconsistency. We evaluate our tool on five publicly available logical models. We perform random changes considering several parameter configurations to assess the tool repairing capabilities. Whenever a model is repaired under the time limit, the tool successfully produces the optimal solutions to repair the model. Instances were generated without the previous limitation to validate this extended approach.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["ModRev", "Model Revision", "Logical Models", "Answer Set Programming"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: 'https://filipegouveia.github.io/ModRev/'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
- ModRev

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

