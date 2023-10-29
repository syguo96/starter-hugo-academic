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
    content:
      title: Recent Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: sguo26v@gmail.com
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
