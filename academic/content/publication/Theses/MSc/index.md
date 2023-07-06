---
title: "Protein design using answer set programming"

draft: false

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2012-11-05T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: In *Journal of Computational Biology*
#publication_short: In *JCB*

abstract: "Different proteins have different functions determined by its structure. Proteins are a sequence of amino acids folded into a three-dimensional structure. Each amino acid is formed by an amine group, a carboxyl group and a side-chain. The side-chain is specific for each amino acid and each amino acid can have numerous possible side-chain conformations, called rotamers. A protein has an energy associated and this energy depends on the amino acids and side-chain that form the protein. Predicting the set of amino acids and respective side-chain that minimizes the total energy of a protein is therefore a very important problem, called protein design. In this work we develop a program to solve the protein design problem using Answer Set Programming. Answer Set Programming (ASP) is an approach to declarative solving problems. This work describes the ASP program implemented to solve protein design problems, using the ASP grounder gringo and the ASP solver clasp to search for the answer sets of the program. Two approaches of the protein design problem were considered: one considered that the amino acids of the protein to design are kept fixed; the other considered that the amino acids are not kept fixed and therefore the amino acids and respective side-chains must be determined. In this work were made two implementations in ASP for the protein design problem. One is a simple codification and the other uses a multi-criteria optimization. Moreover, there were implemented three algorithms of dead-end elimination (DEE): Original DEE; Simple Goldstein; and Simple Split."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ["Protein Design", "Answer Set Programming"]

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
links:
- name: MSc Thesis
  url: /publication/theses/msc/MSc.pdf
- name: Extended Abstract
  url: https://fenix.tecnico.ulisboa.pt/downloadFile/395144612108/ExtendedAbstract-MEIC-T-63543-JoaoGouveia.pdf

url_pdf: ''
url_code: ''
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
projects: []
#- ModRev

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

