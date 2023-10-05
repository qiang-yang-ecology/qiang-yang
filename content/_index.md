---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 90%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 50%
      icon: terminal
      icon_pack: fas
      name: bash
    title: Skills
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: German Centre for Integrative Biodiversity Research (iDiv) Halle-Jena-Leipzig
      #company_logo: org-GC
      company_url: "https://www.idiv.de/en/index.html"
      date_end: ""
      date_start: "2022-02-01"
      description: Synthesizing how plant-pollinator interactions change along environmental gradients
      location: Leipzig, Germany
      title: Postdoctoral researcher
    - company: University of Konstanz
      #company_logo: org-x
      company_url: "https://www.uni-konstanz.de/en/"
      date_end: "2022-01-31"
      date_start: "2018-05-15"
      description: Exploring the drivers and consequences of alien plants naturalization at the global scale
      location: Konstanz, Germany
      title: Postdoctoral researcher
    - company: Trinity College Dublin
      #company_logo: org-x
      company_url: "https://www.tcd.ie/"
      date_end: "2013-05-31"
      date_start: "2012-10-01"
      location: Dublin, Ireland
      title: Lab assistant
    title: Work Experience
  design:
    columns: "2"
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Ecological Stability
      tag: Ecological Stability
    - name: Biological Invasions
      tag: Biological Invasions
#    - name: Marine and Freshwater Biology
#      tag: Marine and Freshwater Biology
    - name: Ecological Network
      tag: Ecological Network
    default_button_index: 0
    filters:
      folders:
      - project
    title: Projects
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Recent Publications
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    count: 5
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts
- block: contact
  content:
    address:
      city: Leipzig
      country: Germany
      country_code: DE
      postcode: "04109"
      region: Saxony
      street: Puschstraße 4
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Qiang__Yang
      name: DM Me
    - icon: researchgate
      icon_pack: fab
      link: https://www.researchgate.net/profile/Qiang-Yang-8
      name: Follow Me
    
    email: qiang.yang@idiv.de
#    form:
#      formspree:
#        id: null
#      netlify:
#        captcha: false
#      provider: netlify
#    subtitle: null
    text: If you would like to talk about science or explore collaborative prospects, please don't hesitate to reach out via my email address.
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
