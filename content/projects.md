---
title: 'Projects'
_build:
  render: never
  list: never
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    id: projects
    anchor: projects
    content:
      title: Recent Projects
      text: Here are some projects I have worked on this year.
      filters:
        folders:
          - project
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
