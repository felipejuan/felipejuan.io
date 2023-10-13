---
# Leave the homepage title empty to use the site title
title: Felipe Juan
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Skills
      items:
        - name: R
          description: 
          icon: r-project
          icon_pack: fab
        - name: Python
          description: 
          icon: python
          icon_pack: fab
        - name: Stata
          description: 
          icon: stata
          icon_pack: svg
  - block: experience
    content:
      title: Teaching Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Summer Fellow
          company: American Economic Association Summer Program
          company_url: 'https://www.aeaweb.org/about-aea/committees/AEASP'
          company_logo: 
          location: Washington
          date_start: '2023-06-01'
          date_end: '2023-08-01'
          description: Teaching Fellow for Advanced Econometrics
        - title: Summer Fellow
          company: American Economic Association Summer Program
          company_url: 'https://www.aeaweb.org/about-aea/committees/AEASP'
          company_logo: 
          location: Washington
          date_start: '2022-06-01'
          date_end: '2022-08-01'
          description: Teaching Fellow for Advanced Econometrics
        - title: Summer Fellow
          company: American Economic Association Summer Program
          company_url: 'https://www.aeaweb.org/about-aea/committees/AEASP'
          company_logo: 
          location: Washington
          date_start: '2021-06-01'
          date_end: '2021-08-01'
          description: Teaching Fellow for Advanced Econometrics
        - title: Instructor
          company: Howard University
          company_url: ''
          company_logo: 
          location: Washington
          date_start: '2020-08-20'
          date_end: '2020-12-15'
          description: Taught introductory macroeconomics
    design:
      columns: '2'
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Fellowships & &shy; Grants'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: '2024-08-31'
          date_start: '2023-09-01'
          description: ''
          organization: Russell Sage Foundation
          organization_url: https://www.russellsage.org/
          title: 'Dissertation Research Grant'
          url: 'https://www.russellsage.org/awarded-project/importance-considering-state-eligibility-requirements-equitable-unemployment'
        - certificate_url: 
          date_end: '2024-07-07'
          date_start: '2023-08-07'
          description: 
          organization: Mercatus Center
          organization_url: https://www.mercatus.org/
          title: Adam Smith Fellow
          url: https://www.mercatus.org/students/fellows/felipe-juan
        - certificate_url: https://www.nasi.org/pressrelease/kilolo-kijakazi-fellowship-program-fellows/
          date_end: ''
          date_start: '2022-06-01'
          description: ''
          organization: The Policy Academies and The National Academy of Social Insurance
          organization_url: https://www.datacamp.com
          title: Kilolo Kijikazi Fellow
          url: 'https://www.thepolicyacademies.org/'
    design:
      columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
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
        - name: Unemployment Insurance 
          tag: Unemployment Insurance
        - name: Metaverse
          tag: Metaverse
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="economist" >}}
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
        exclude_featured: true
    design:
      columns: '2'
      view: citation
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
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Get in touch with me about anything.
      # Contact (add or remove contact options as necessary)
      email: felipe.juan@bison.howard.edu
      phone: 5126638213
      appointment_url: 
      address:
        street: 
        city: Washington
        region: DC
        postcode: '20011'
        country: United States
        country_code: US
      directions: 
      office_hours:
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/soyfelipejuan'
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
