---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-12
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    id: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Graduate Research Assistant
          company: Dept. of Earth Sciences, Dartmouth College
          company_url: ''
          company_logo: dpine
          location: New Hampshire, USA
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              Responsibilities include:
              * Analysing
              * Modelling
              * Deploying
        - title: Research Intern and Working Student
          company: Marine Biogeochemistry, Alfred Wegener Institute
          company_url: ''
          company_logo: AWI
          location: Bremerhaven, Germany
          date_start: '2020-08-01'
          date_end: '2022-05-31'
          description: Taught electronic engineering and researched semiconductor physics.
        - title: Undergraduate Research Assistant
          company: Dept. of Earth and Environmental Sciences, Jacobs University Bremen
          company_url: ''
          company_logo: jub
          location: Bremen, Germany
          date_start: '2020-08-01'
          date_end: '2022-05-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: vigneshgokulmenon@gmail.com
      phone: 8606985735
      address:
        street: 19 Fayerweather Hill Rd
        city: Hanover
        region: NH
        postcode: '03755'
        country: United States
        country_code: US
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '37.4275'
        longitude: '-122.1697'  
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
