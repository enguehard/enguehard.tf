---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: about.biography
    id: about-bio
    content:
      title:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin2
#  - block: collection
#    id: talks
#    content:
#      title: News
#      filters:
#        folders:
#          - event
#      text: |-
#        - I will present 'Endemic Violence...' at the EHES meeting in Vienna (9/23). 
#        - I will present 'Lewis and Malthus...' at the Cliometric Society World Meeting in Dublin (7/23).
#        - I organize the following workshop (9/23): 
#        
#        __      
#    design:
#      columns: '1'
#      view: compact

#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: markdown
#    id: text
#    content:
#      title: text
#      subtitle: ''
#      text: |-
#        text
    design:
      columns: '1'


  - block: experience
    id: experience
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
        - title: PhD Candidate (French Government Contract)
          company: ENS de Lyon
          company_url: 'https://www.ens-lyon.fr/'
          company_logo: logo-ensl
          location: France
          date_start: '2021-09-01'
          date_end: ''
          description: |2-
              Teaching duties include:

              * TA: Mathematics for Economists (3rd-year students at ENS Lyon)
              * Main instructor: Fundamentals of Micro- and Macroeconomics (graduate business students from EM Lyon)
        - title: Lecteur
          company: Lady Margaret Hall, University of Oxford
          company_url: 'https://www.lmh.ox.ac.uk/'
          company_logo: logo-lmh
          location: United Kingdom
          date_start: '2020-10-01'
          date_end: '2021-06-30'
          description: Taught French conversation and essay (1st- to 4th-year).
        - title: Macroeconomic Research Assistant
          company: Chair Energy & Prosperity 
          company_url: 'http://www.chair-energy-prosperity.org/en/'
          company_logo: logo-afd
          location: France
          date_start: '2018-09-01'
          date_end: '2019-02-28'
          description: Based at the French Development Agency (AFD), I worked on coupling the macroeconomic model GEMMES with the climate model Loveclim.
        - title: Mathematics Instructor
          company: Lycée Lakanal 
          company_url: ''
          company_logo: logo-llk
          location: France
          date_start: '2016-09-01'
          date_end: '2019-02-28'
          description: Math oral exam training for second-year liberal arts undergraduate students.                      
    design:
      columns: '2'

  - block: portfolio
    id: research
    content:
      title: Research
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
#      buttons:
#        - name: All
#          tag: '*'
#        - name: State Capacity
#          tag: State Capacity
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: compact
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
         Email is the best way to reach me.
      # Contact (add or remove contact options as necessary)
      email: joseph.enguehard@ens-lyon.fr
      #phone: 888 888 88 88
      #appointment_url: 'https://calendly.com'
      address:
        street: ENS, 15 parvis Descartes
        city: 69007 Lyon
        region: France
        postcode:
        country: France
        country_code: FRA
      directions: CERGIC, Office D4.004
      #office_hours:
        #- 'Monday 10:00 to 13:00'
        #- 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: Twitter
          link: 'https://twitter.com/EnguehardJoseph'
  
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'
---
