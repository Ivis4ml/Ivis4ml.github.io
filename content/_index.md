---
title: ''
date: 2024-01-01
type: landing

design:
  spacing: "6rem"

sections:
  - block: about.biography
    id: about
    content:
      title: ''
      username: admin
    design:
      background:
        image:
          filename: hero-bg.jpg
          filters:
            brightness: 0.3
          parallax: true
          position: center
          size: cover
        text_color_light: true

  - block: collection
    id: posts
    content:
      title: Recent Writing
      subtitle: ''
      text: ''
      count: 5
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
      offset: 0
      order: desc
    design:
      view: compact
      columns: '2'

  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: citation

  - block: collection
    id: projects
    content:
      title: Open Source
      count: 10
      filters:
        folders:
          - project
    design:
      view: showcase
      columns: 2

  - block: contact
    id: contact
    content:
      title: Contact
      email: xinchoubiology@gmail.com
      contact_links:
        - icon: github
          icon_pack: fab
          name: GitHub
          link: https://github.com/Ivis4ml
        - icon: x-twitter
          icon_pack: fab
          name: X / Twitter
          link: https://x.com/xybuyibuer
      autolink: true
    design:
      columns: '2'
---
