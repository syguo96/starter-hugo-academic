---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: news
    content:
      title: ''
      subtitle: ''
      text: ''   # optional intro text
      count: 6   # how many items to show
      filters:
        folders:
          - news   # read from content/news/*
        author: ''
        category: ''
        tag: ''
        publication_type: ''
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      offset: 0
      sort_by: 'Date'
      sort_ascending: false
    design:
      view: compact   # nice condensed list view
      columns: '1'
---
