---
title: "Pragmatic Fairness: Optimizing Policies with Outcome Disparity Control"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Limor Gultchin
  - admin
  - Alan Malek
  - Silvia Chiappa
  - Ricardo Silva


date: '2022-12-15T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *NeurIPS 2022 Workshop on Algorithmic Fairness through the Lens of Causality and Privacy*

abstract: We introduce a causal framework for designing optimal policies that satisfy fairness constraints. We take a pragmatic approach asking what we can do with an action space available to us and only with access to historical data. We propose two different fairness constraints, a moderation breaking constraint which aims at blocking moderation paths from the action and sensitive attribute to the outcome, and by that at reducing disparity in outcome levels as much as the provided action space permits; and an equal benefit constraint which aims at distributing gain from the new and maximized policy equally across sensitive attribute levels, and thus at keeping pre-existing preferential treatment in place or avoiding the introduction of new disparity. We introduce practical methods for implementing the constraints and illustrate their uses on experiments with semi-synthetic models.
tags: []

featured: false

url_pdf: https://arxiv.org/abs/2301.12278.pdf
url_code: https://github.com/limorigu/pragmaticfairness
---
