---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  #    - block: experience
  #      content:
  #        title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
  #        date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      #   items:
      #      - title: CEO
      #        company: GenCoin
      #        company_url: ''
      #        company_logo: org-gc
      #        location: California
      #        date_start: '2021-01-01'
      #        date_end: ''
      #        description: |2-
      #            Responsibilities include:

      #            * Analysing
      #            * Modelling
      #           * Deploying
      #      - title: Professor of Semiconductor Physics
      #        company: University X
      #        company_url: ''
      #        company_logo: org-x
      #        location: California
      #        date_start: '2016-01-01'
      #        date_end: '2020-12-31'
      #        description: Taught electronic engineering and researched semiconductor physics.
  #      design:
  #        columns: '2'

  - block: collection
    id: Publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

  - block: contact
    id: contact
    content:
      email: xcwang [AT] psu.edu
      address:
        street: E348 Westgate Building
        city:  State College
        region: PA
        postcode: '16801'
        country: United States
        country_code: US



    design:
      columns: '2'
---
