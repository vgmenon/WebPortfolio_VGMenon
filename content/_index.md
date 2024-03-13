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
              * Plan and conduct microcosm experiments (ship-board as well as roller tank experiments in laboratory) and mesocosm experiments to understand the effect of lithogenic mineral dust on particle aggregation and carbon flux in the surface ocean.
              * Understand the dynamics of organo-mineral floc formation and its impact on carbon export from the surface ocean.
              * Methodology: Particle analysis, Spectrophotometry, Microscopy, Solid Phase Extraction, Mass Spectrometry
        - title: Research Intern and Working Student
          company: Marine Biogeochemistry, Alfred Wegener Institute
          company_url: ''
          company_logo: AWI
          location: Bremerhaven, Germany
          date_start: '2020-08-01'
          date_end: '2022-05-31'
          description: |2-
              * Carry out field sampling for soil pore water and lysimeter samples, and prepare nutrient, cations, isotope, DIC and Alkalinity samples for measurement on a weekly basis.
              * Estimate the critical shear velocity of Olivine sample by the implementation of a Gust chamber for simulating boundary layer shear stress conditions to determine the regimes to carry out a potential Enhanced weathering project.
        - title: Undergraduate Research Assistant
          company: Jacobs University Bremen
          company_url: ''
          company_logo: jub
          location: Bremen, Germany
          date_start: '2020-08-01'
          date_end: '2022-05-31'
          description: |2-
              * Sediment characteristics and dynamics analysis with the aid of instruments such as LISST-100X, Cameras, Aqualogger, and experimental set up involving water flume, Water-column simulator, and settling column.
              * Analysis of datasets for particle size distribution and settling velocity using Python, MATLAB and Image analysis using ImageJ Fiji software.
              * Preparation of bottles for sample handling and processing, following certain acid-bath/wash and GEOTRACES protocol as needed.
              * Setting up ICP-MS and ICP-OES and sample preparation.
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
      # buttons:
       # - name: All
       #   tag: '*'
       # - name: Marine Biogeochemistry
       #   tag: Clay carbon
       # - name: Marine Chemistry
       #   tag: rainbow
       # - name: Carbon Sequestration
       #   tag: Clay carbon
       # - name: Carbon Sequestration
       #   tag: ERW
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    id: experience
    content:
      title: Research Cruises
      items:
        - title: EN710 - Penobscot Bay Hg
          company: RV Endeavor
          company_url: ''
          company_logo: uri
          location: Gulf of Maine, USA
          date_start: '2023-10-31'
          date_end: '2023-11-10'
          description: |2-
        - title: EN699 - Clay, carbon, oceans
          company: RV Endeavor
          company_url: ''
          company_logo: uri
          location: Gulf of Maine, USA
          date_start: '2023-04-01'
          date_end: '2023-04-10'
          description: |2-
        - title: HE597 - JUB & POLMAR Graduate school educational cruise
          company: RV Heincke
          company_url: ''
          company_logo: awi
          location: North Sea - Heligoland
          date_start: '2022-04-22'
          date_end: '2022-04-28'
          description: |2-
        - title: M176/2 - Rainbow nonboyant hydrothermal plume GEOTRACES study
          company: RV Meteor
          company_url: ''
          company_logo: geomar-logos-ids9ovgEuF
          location: Rainbow hydrothermal vent field, MAR
          date_start: '2022-08-30'
          date_end: '2022-10-06'
          description: |2-
        - title: HE575 - Oceanography Field Lab
          company: RV Heincke
          company_url: ''
          company_logo: awi
          location: German Bight
          date_start: '2021-04-27'
          date_end: '2021-04-30'
          description: |2-
    design:
      columns: '2'
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
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
        - title: MS Earth Sciences
          company: Dartmouth College
          company_url: 'https://earthsciences.dartmouth.edu'
          company_logo: dpine
          location: New Hampshire, USA
          date_start: '2022-09-01'
          date_end: ''
          description: |2-
              Awards:
              * Dartmouth Graduate Student Fellowship {2022-Present} |
              * Guarini School of Graduate and advanced studies travel award (ASLO-ASM'23)
        - title: BSc Earth and Environmental Sciences
          company: Constructor (formerly Jacobs) University Bremen
          company_url: 'https://constructor.university/programs/undergraduate-education/earth-environmental-sciences'
          company_logo: jub
          location: Bremen, Germany
          date_start: '2020-08-01'
          date_end: '2022-05-31'
          description: |2-
              * Grade: 1.20 - German Grading Scale
              * Awards: Jacobs Merit Scholarship {2019-2022}
    design:
      columns: '2'
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
        latitude: '43.705933' 
        longitude: '-72.286450'  
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
