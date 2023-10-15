---
title: "Felipe Juan"
date: "2022-10-24"
type: landing

sections:
- block: about.biography
  id: about
  content:
    username: admin
    text: null
- block: features
  content:
    title: Skills
    items:
    - name: R
      description: null
      icon: "r-project"
      icon_pack: fab
    - name: Python
      description: null
      icon: python
      icon_pack: fab
    - name: Stata
      description: null
      icon: stata
      icon_pack: svg
- block: experience
  content:
    title: Teaching Experience
    date_format: Jan 2006
    items:
    - title: Summer Fellow
      company: American Economic Association Summer Program
      company_url: "https://www.aeaweb.org/about-aea/committees/AEASP"
      company_logo: null
      location: Washington
      date_start: "2023-06-01"
      date_end: "2023-08-01"
      description: Teaching Fellow for Advanced Econometrics
    - title: Summer Fellow
      company: American Economic Association Summer Program
      company_url: "https://www.aeaweb.org/about-aea/committees/AEASP"
      company_logo: null
      location: Washington
      date_start: "2022-06-01"
      date_end: "2022-08-01"
      description: Teaching Fellow for Advanced Econometrics
    - title: Summer Fellow
      company: American Economic Association Summer Program
      company_url: "https://www.aeaweb.org/about-aea/committees/AEASP"
      company_logo: null
      location: Washington
      date_start: "2021-06-01"
      date_end: "2021-08-01"
      description: Teaching Fellow for Advanced Econometrics
    - title: Instructor
      company: Howard University
      company_url: ''
      company_logo: null
      location: Washington
      date_start: "2020-08-20"
      date_end: "2020-12-15"
      description: Taught introductory macroeconomics
  design:
    columns: '2'
- block: accomplishments
  content:
    title: Fellowships & &shy; Grants
    subtitle: null
    date_format: Jan 2006
    items:
    - certificate_url: null
      date_end: "2024-08-31"
      date_start: "2023-09-01"
      description: ''
      organization: Russell Sage Foundation
      organization_url: https://www.russellsage.org/
      title: Dissertation Research Grant
      url: "https://www.russellsage.org/awarded-project/importance-considering-state-eligibility-requirements-equitable-unemployment"
    - certificate_url: null
      date_end: "2024-07-07"
      date_start: "2023-08-07"
      description: null
      organization: Mercatus Center
      organization_url: https://www.mercatus.org/
      title: Adam Smith Fellow
      url: "https://www.mercatus.org/students/fellows/felipe-juan"
    - certificate_url: 
      date_end: ''
      date_start: "2022-06-01"
      description: ''
      organization: The Policy Academies and The National Academy of Social Insurance
      organization_url: "https://www.nasi.org/pressrelease/kilolo-kijakazi-fellowship-program-fellows/"
      title: Kilolo Kijikazi Fellow
      url: https://www.thepolicyacademies.org/
  design:
    columns: '2'
- block: collection
  id: posts
  content:
    title: Recent Posts
    subtitle: ''
    text: ''
    count: 5
    filters:
      folders: 
        - post
      author: ''
      category: ''
      tag: ''
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      publication_type: ''
    offset: 0
    order: desc
  design:
    view: compact
    columns: '2'
# - block: portfolio
#   id: projects
#   content:
#     title: Projects
#     filters:
#       folders: project
#     default_button_index: 0
#     buttons:
#     - name: All
#       tag: '*'
#     - name: Unemployment Insurance
#       tag: Unemployment Insurance
#     - name: Metaverse
#       tag: Metaverse
#   design:
#     columns: '1'
#     view: showcase
#     flip_alt_rows: no
- block: markdown
  content:
    title: Gallery
    subtitle: ''
    text: |-
      {{< gallery album="economist" >}}
  design:
    columns: '1'
# - block: collection
#   id: featured
#   content:
#     title: Featured Publications
#     filters:
#       folders: publication
#       featured_only: yes
#   design:
#     columns: '2'
#     view: card
# - block: collection
#   content:
#     title: Recent Publications
#     text: |-
#       {{% callout note %}}
#       Quickly discover relevant content by [filtering publications](./publication/).
#       {{% /callout %}}
#     filters:
#       folders: publication
#       exclude_featured: yes
#   design:
#     columns: '2'
#     view: citation
# - block: collection
#   id: talks
#   content:
#     title: Recent & Upcoming Talks
#     filters:
#       folders: event
#   design:
#     columns: '2'
#     view: compact
# - block: tag_cloud
#   content:
#     title: Popular Topics
#   design:
#     columns: '2'
- block: contact
  id: contact
  content:
    title: Contact
    subtitle: null
    text: Get in touch with me about anything.
    email: felipe.juan@bison.howard.edu
    phone: null
    appointment_url: null
    address:
      street: null
      city: Washington
      region: DC
      postcode: '20011'
      country: United States
      country_code: US
    directions: null
    office_hours: null
    contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: https://twitter.com/soyfelipejuan
    autolink: yes
    form:
      provider: netlify
      formspree:
        id: null
      netlify:
        captcha: no
  design:
    columns: '2'
---
