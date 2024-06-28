---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: CV
        url: uploads/MattSampson_cv_2024.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: pyramid.png
          filters:
            brightness: 0.8
          size: cover
          position: center
          parallax: false
  #- block: markdown
  #  content:
  #    title: 'My Research'
  #    subtitle: ''
  #    text: |-
  #      I'm a researcher working on developing novel machine learning techniques for science. 
  #      Please reach out to collaborate!
  #  design:
  #    columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
