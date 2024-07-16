---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
  - id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
   - block: collection
    content:
      title: News
      filters:
        folders:
          - news
        exclude_features: false
      design:
        column: '2'
        view: 'date-title-summary'
        spacing:
          padding: [0, 0, 0, 0]
  - block: collection
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Visit my [Google Scholar profile](https://scholar.google.co.uk/citations?hl=en&pli=1&user=GRGyzn4AAAAJ) or search over [my publication page](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Doctoral Fellow
          company: Cambridge-Tübingen Fellowship
          location: United Kingdom and Germany
          date_start: '2021-10-01'
          date_end: ''
        - title: Quantitative Strategist
          company: Goldman Sachs International
          location: London
          date_start: '2019-07-01'
          date_end: '2020-07-01'
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Premium Research Bursary 
          date_end: '2022-09-30'
          date_start: '2021-10-01'
          description: 'Awarded £15,609'
          organization: University of Cambridge
          url: 'https://www.cst.cam.ac.uk/admissions/phd/rs-premium'
        - title: Cambridge Tübingen PhD Fellowship in Machine Learning
          date_end: '2025-09-30'
          date_start: '2021-10-01'
          description: 'Awarded ~ £168,249'
          organization: Max Planck Institute for Intelligent Systems
          url: 'https://mlg.eng.cam.ac.uk/cambridge_tubingen_phd_fellowships/'
        - title: Dean's List
          date_start: '2021-12-01'
          organization: University College London
          description:
          date_end: ''
        - title: Openshaw Prize, Exhibition & Foundation Scholarship
          date_start: '2015-10-01'
          date_end: '2018-06-30'
          organization: Queens' College, University of Cambridge
      columns: '2'
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: experience
    content:
      title: Services
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Intern Mentoring
          company: Max Planck Institute for Intelligent Systems
          location: Germany
          date_start: '2023-06-05'
          date_end: '2023-08-25'
          description: Mentoring [Xianjun Davin Choo](https://cxjdavin.github.io/) during his intern period at MPI on out-of-variable generalization. 
        - title: Workshop Organizer
          company: Causal Representation Learning
          company_url: 'https://crl-tuebingen-2023.github.io/'
          location: Germany
          date_start: '2023-04-17'
          date_end: '2023-04-19'
        - title: Workshop Organizer
          company: Causal Digital Twins
          company_url: 'https://ellis.eu/news/members-of-the-ellis-community-meet-for-the-first-unconference-in-spain'
          location: Spain
          date_start: '2023-01-04'
          date_end: '2023-01-04'
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: sguo26v@gmail.com
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'
---
