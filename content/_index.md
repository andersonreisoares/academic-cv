---
# Leave the homepage title empty to use the site title
title: ''
date: 2024-02-20
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
  - block: experience
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
        - title: Senior Data Scientist 
          company: Bayer Crop Science Per Cognizant Brazil
          company_url: ''
          location: Remote
          date_start: '2021-01-01'
          date_end: ''
          description: Responsible for the development of workflows and frameworks for subfield monitoring to provide agronomic insights and precriptive actions.          
        - title: Research Collaborator
          company: Brazilian National Institute For Space Research (INPE)
          company_url: 'https://brazildatacube.dpi.inpe.br/portal/explore'
          location: São José dos Campos
          date_start: '2019-06-01'
          date_end: '2020-12-31'
          description: Developed and explored new techniques for land use and land cover mapping based on satellite imagery time series. Developed the stmetrics package.
        - title: CO-Founder / CKO
          company: Nitentech Tecnologia Da Informação Ltda
          location: São Paulo
          date_start: '2018-12-01'
          date_end: '2020-11-30'
          description: Chief of knowledge operations, responsible for the development of the system, from database modelling to UI design
        - title: GIS SPECIALIST 
          company: INCITI – Pesquisa e inovação para as cidades
          company_url: 'https://inciti.org/projeto/parque-capibaribe/'
          location: Recife
          date_start: '2013-11-01'
          date_end: '2014-04-30'
          description: Responsible to provide spatial analysis and data management to support urban planning decisions.
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  - block: publication
    id: publication
    content:
      title: Recent Publications
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
      title: Contact
      subtitle: If you want to get in touch, send an email or use one of the resources indicated in this page.
      # Contact (add or remove contact options as necessary)
      email: andersonreis.geo@gmail.com
      address:
        street: ''
        city: João Pessoa
        region: PB
        postcode: ''
        country: Brazil
        country_code: BR
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
