---
widget: pages
active: true
headless: true

title: "Recent News"
subtitle: ""

# Order on the homepage.
# Check content/home/about.md for its weight (often 10);
# use a slightly larger number so this appears right under your photo.
weight: 20

content:
  # Pull items from content/news/*
  page_type: news

  # Number of items to show in the list
  count: 6
  offset: 0
  order: desc

  filters:
    tag: ""
    category: ""
    publication_type: ""
    exclude_featured: false
    exclude_future: true
    exclude_past: false

design:
  view: compact
  columns: "1"

# We'll use this to attach custom CSS for the rolling panel
advanced:
  css_class: "news-scroll"
---
