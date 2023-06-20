---
date: "2022-10-24"
sections:
- block: hero
  content:
    image:
      filename: hero-fs.png
    text: |-
      Welcome to Fluffy Sciences, Jill MacKay's corner of the internet.

      You can find out more about me, my work, and the resources I make available to try and make life a little easier.

    title: Jilly MacKay / FluffySciences
  design:
    background:
      gradient_end: '#a3c3b2'
      gradient_start: '#86a193'
      text_color_light: true
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: collection
  content:
    date_format: Jan 2006
    items:
    - company: University of Edinburgh
      company_logo: org-gc
      company_url: "www.ed.ac.uk"
      date_end: ""
      date_start: "2016-06-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: Edinburgh
      title: Senior Lecturer (Veterinary Science Education)
    - company: SRUC
      company_logo: org-x
      company_url: ""
      date_end: "2016-05-30"
      date_start: "2013-01-01"
      description: MSc Coordinator ( International Animal Welfare Ethics and Law)
      location: Edinburgh, Scotland
      title: Lecturer
    title: Work
  design:
    columns: "2"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: OERs / Teaching
  design:
    columns: "2"
    view: card
  id: oers
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
    title: Books / Publications
  design:
    columns: "2"
    view: citation
  id: publication
- block: collection
  content:
    filters:
      folders:
      - event
    title: Public Engagement
  design:
    columns: "2"
    view: compact
  id: talk
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
  id: post
- block: tag_cloud
  content:
    title: What do I talk about?
  design:
    columns: "2"
- block: contact
  content:
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/jilly_mackay
      name: DM Me
    - icon: mastodon
      icon_pack: fab
      link: https://mastodon.scot/@jillymackay
      name: I'm on Mastodon
    office_hours:
      Please note, I work condensed hours Monday-Thursday
    text: The best way to contact me is to reach out via my Edinburgh email address, but you may also get a good response on Twitter or Mastodon!
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
