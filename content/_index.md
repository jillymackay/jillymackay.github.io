---
date: "2023-06-22"
sections:
- block: hero
  content:
    image:
      filename: hero-fs.png
    text: |-
      Welcome to Fluffy Sciences, my little corner of the internet. 
      
      This page is set up to showcase some of my work on research methodology and science education. The 'Fluffy Sciences' name comes from my history working in veterinary sciences. 
      
    title: Jilly MacKay 
  design:
    background:
      gradient_end: '#a3c3b2'
      gradient_start: '#597366'
      text_color_light: true
- block: about.biography
  content:
    title: Biography
    username: admin
  id: about
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: University of Edinburgh
      company_url: "www.ed.ac.uk"
      date_end: ""
      date_start: "2016-06-01"
      description: |2-
          Responsibilities include:

          * Quality Assurance for teaching-related data
          * Developing research competencies across the school
          * Teaching research methodology at UG and PG
      location: Edinburgh, Scotland
      title: Senior Lecturer (Veterinary Science Education)
    - company: SRUC
      company_url: ""
      date_end: "2016-06-01"
      date_start: "2013-01-01"
      description: |2-
          MSc Coordinator
          
          * (International Animal Welfare Ethics and Law)
          
          Lecturer / Course Organiser
          
          * (Animal Behaviour and Welfare 3rd Year)
          * (Animal Welfare 2nd Year)
      location: Edinburgh, Scotland
      title: Lecturer
    title: Work
  design:
    columns: "2"
- block: portfolio
  id: research
  content:
    title: Research
    subtitle: A collection of projects that I think are worth sharing
    text: You can look for something specific by using the buttons below, or see all [projects here](./project). 
    filters:
        # Folders to display content from
      folders:
        - project
        # Only show content with these tags
      tags: []
        # Exclude content with these tags
      exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
      kinds:
        - page
    # Field to sort by, such as Date or Title
    sort_by: 'Date'
    sort_ascending: false
    # Default portfolio filter button
    # 0 corresponds to the first button below and so on
    # For example, 0 will default to showing all content as the first button below shows content with *any* tag
    default_button_index: 0
    # Filter button toolbar (optional).
    # Add or remove as many buttons as you like.
    # To show all content, set `tag` to "*".
    # To filter by a specific tag, set `tag` to an existing tag name.
    # To remove the button toolbar, delete the entire `buttons` block.
    buttons:
      - name: All
        tag: '*'
      - name: Research Methods
        tag: research_methods
      - name: Widening Participation
        tag: wp
  design:
    # See Page Builder docs for all section customization options.
    # Choose how many columns the section has. Valid values: '1' or '2'.
    columns: '1'
    # Choose a listing view
    view: showcase
    # For Showcase view, flip alternate rows?
    flip_alt_rows: true
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - resources
    title: OERs / Teaching
    text: I have a number of teaching resources which are available for others to use as they see fit. Some of the highlights are here or [you can look through the whole list here](./resources)
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
    title: Talks
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
  taxonomy: tags
  count: 20
  design:
    columns: "2"
- block: contact
  content:
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/jilly_mackay
      name: I'm on Twitter (for my sins)
    - icon: mastodon
      icon_pack: fab
      link: https://mastodon.scot/@jillymackay
      name: I'm on Mastodon
    office_hours:
      Please note, I work condensed hours
    text: The best way to contact me is to reach out via my Edinburgh email address, but you may also get a good response on Twitter or Mastodon!
    title: Contact
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
