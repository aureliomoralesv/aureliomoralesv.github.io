---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
#    design:
#      background:
#        gradient_end: '#1976d2'
#        gradient_start: '#004ba0'
#        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
    design:
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0'] 
  - block: skills
    content:
      title: Skills
      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
      username: admin
    design:
      columns: '1'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Pre sales engineer
          company: Telefónica del Perú S.A.A.
          company_url: ''
#          company_logo: org-gc
          location: Lima, Perú
          date_start: '2006-05-01'
          date_end: '2008-01-01'
          description: Data communications pre sales engineer for Poder Judicial, CCFFAA, ONP, FAP, Minedu, SIMA
        - title: Senior support engineer
          company: Telefónica Empresas Perú S.A.A.
          company_url: ''
#          company_logo: org-gc
          location: Lima, Perú
          date_start: '2001-09-01'
          date_end: '2006-04-01'
          description: Support engineer for Sun Microsystems platforms in Telefonica group
        - title: Project engineer
          company: Telefónica Sistemas Sucursal del Peru S.A.
          company_url: ''
#          company_logo: org-gc
          location: Lima, Perú
          date_start: '1996-07-01'
          date_end: '2001-08-01'
          description: Pre sales engineer for computing platforms in Telefonica group
    design:
      columns: '2'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
  - block: experience
    content:
      title: Academic Experience
      date_format: Jan 2006
      items:
        - title: Professor
          company: Universidad Nacional de Ingeniería
          company_url: 'https://www.uni.edu.pe/'
#          company_logo: org-x
          location: Lima, Perú
          date_start: '2012-06-01'
          date_end: ''
          description: Taught electronics engineering courses (undergraduate) and researched on FPGA applications.
        - title: Associate Professor
          company: Universidad Nacional de Ingeniería
          company_url: 'https://www.uni.edu.pe/'
#          company_logo: org-x
          location: Lima, Perú
          date_start: '1994-04-01'
          date_end: '2012-05-31'
          description: Taught electronics engineering courses (undergraduate and graduate) and researched on FPGA applications.
        - title: Assistant Professor
          company: Universidad Nacional de Ingeniería
          company_url: 'https://www.uni.edu.pe/'
#          company_logo: org-x
          location: Lima, Perú
          date_start: '1989-10-01'
          date_end: '1992-09-01'
          description: Taught electronics engineering courses (undergraduate).
    design:
      columns: '2'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
#  - block: accomplishments
#    content:
#      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
#      title: 'Accomplish&shy;ments'
#      subtitle:
#      # Date format: https://docs.hugoblox.com/customization/#date-format
#      date_format: Jan 2006
#      # Accomplishments.
#      #   Add/remove as many `item` blocks below as you like.
#      #   `title`, `organization`, and `date_start` are the required parameters.
#      #   Leave other parameters empty if not required.
#      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
#      items:
#        - certificate_url: https://www.coursera.org
#          date_end: ''
#          date_start: '2021-01-25'
#          description: ''
#          icon: coursera
#          organization: Coursera
#          organization_url: https://www.coursera.org
#          title: Neural Networks and Deep Learning
#          url: ''
#        - certificate_url: https://www.edx.org
#          date_end: ''
#          date_start: '2021-01-01'
#          description: Formulated informed blockchain models, hypotheses, and use cases.
#          icon: edx
#          organization: edX
#          organization_url: https://www.edx.org
#          title: Blockchain Fundamentals
#          url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
#        - certificate_url: https://www.datacamp.com
#          date_end: '2020-12-21'
#          date_start: '2020-07-01'
#          description: ''
#          icon: datacamp
#          organization: DataCamp
#          organization_url: https://www.datacamp.com
#          title: 'Object-Oriented Programming in R'
#          url: ''
#    design:
#      columns: '2'
#      spacing:
#        # Customize the section spacing. Order is top, right, bottom, left.
#        padding: ['20px', '0', '20px', '0']

#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
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
        - name: fp32adder VLSI
          tag: vlsi
        - name: On-Chip CSR
          tag: CSR
        - name: On-Chip HTR
          tag: HTR
        - name: RISC Mips
          tag: Mips
        - name: Superscalar CPU
          tag: Superscalar
        - name: Hopfield FPGA
          tag: Hopfield 
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
  - block: collection
    id: publications
    content:
      title: Journal & Conference Papers
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: citation
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
  - block: collection
    content:
      title: Works that reference my research
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/others/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
#     view: card
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
#      subtitle:
#      text: |-
#        Please, complete the form below, giving your full name, e-mail address and a message.
      # Contact (add or remove contact options as necessary)
      email: amorales@uni.edu.pe
      phone: +51 381 6700
#      appointment_url: 'https://calendly.com'
      address:
        street: Av. Túpac Amaru 210
        city: Rimac
        region: Lima
        postcode: '15333'
        country: Perú
        country_code: PE
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Friday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
#        latitude: '37.4275' # for Stanford University
#        longitude: '-122.1697' # for Stanford University
#coordinates for UNI
        latitude:  '-12.017222'
        longitude: '-77.048889'  
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
#      # Automatically link email and phone or display as text?
#      autolink: true
#      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
    design:
      columns: '2'
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
---
