---
title: Iterative Train Scheduling under Disruption with Maximum Satisfiability
subtitle: Check our paper published on [JAIR](https://jair.org/index.php/jair/article/view/14924)!

# Summary for listings and search engines
# summary: Welcome 👋 We know that first impressions are important, so we've populated your new site with some initial content to help you get familiar with everything in no time.

# Link this post with a project
projects: []

# Date published
date: "2024-04-02T00:00:00Z"

# Date updated
lastmod: "2024-04-02T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: true

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- Alexandre Lemos
- admin
- Inês Lynce
- Pedro T. Monteiro

tags:
- SAT
- Train Scheduling

# categories:
# - Demo
# - 教程
---

![Train Scheduling](RailWayV3.png)

<!-- ## Abstract -->

This paper proposes an iterative Maximum Satisfiability (MaxSAT) approach designed to solve train scheduling optimization problems. The generation of railway timetables is known to be intractable for a single track. We consider hundreds of trains on interconnected multi-track railway networks with complex connections between trains. Furthermore, the proposed algorithm is incremental to reduce the impact of time discretization.


The performance of our approach is evaluated with the real-world Swiss Federal Railway (SBB) Crowd Sourcing Challenge benchmark and Periodic Event Scheduling Problems benchmark (PESPLib). The execution time of the proposed approach is shown to be, on average, twice as fast as the best existing solution for the SBB instances. In addition, we achieve a significant improvement over SAT-based solutions for solving the PESPLib instances.


We also analyzed real schedule data from Switzerland and the Netherlands to create a disruption generator based on probability distributions. The novel incremental algorithm allows solving the train scheduling problem under disruptions with better performance than traditional algorithms.

## Info

*DOI:* https://doi.org/10.1613/jair.1.14924

*Published:* Mar 31, 2024

*Keywords:* constraint satisfaction, logic programming, Boolean satisfiability, scheduling


