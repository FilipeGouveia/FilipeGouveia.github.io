---
title: RIGA
summary: Reasoning Over Indirect Discrimination
tags:
    - Automated Reasoning
    - Answer Set Programming
    - Fairness
    - Bias
date: "2023-03-12T00:00:00Z"

authors:
- Inês Lynce
- admin
- Vasco Manquinho


# Optional external URL for project (replaces project detail page).
#external_link: "https://filipegouveia.github.io/ModRev/"

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

#links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/georgecushen
url_code: "https://github.com/FilipeGouveia/Riga"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#slides: example
---

*Refª 2022.03537.PTDC*

**Type:** National Project

**Financed by:** FCT

**Prime Contractor:** R - INESC-ID Lisboa (Other) - Lisboa, Portugal


Project RIGA aims to propose the use of automated reasoning to identify proxy attributes in training datasets without prior background knowledge of the relations between attributes. In project RIGA it is not only desired to identify single attributes that act as proxy attributes of a given protected attribute, but also combinations of attributes that act as proxy attributes. In the latter case, it is considered that two or more unprotected attributes combined act as proxy attributes, where each one of these attributes individually are not proxy attributes. This raises a challenging combinatorial problem.

The goal of project RIGA is the application of logic-based approaches to identify potential proxy attributes (single or combined) in datasets that can lead to discriminatory Machine Learning models. In the identification of proxy attributes, different relations between unprotected and protected attributes are considered, such as equivalence and implication. Moreover, it is considered that a proxy attribute may have a degree of confidence associated. For example, if it is not possible to infer accurately all the values (100%) of a protected attribute from the information of a set of unprotected attributes, but it is possible to infer most of the values (e.g. 90 %), then one may want to consider such set of unprotected attributes as proxy attributes as well.

## Members

 - [Inês Lynce](https://sat.inesc-id.pt/~ines/) (PI)
 - [Filipe Gouveia](https://filipegouveia.github.io/) (Co-PI)
 - [Vasco Manquinho](http://sat.inesc-id.pt/~vmm/)