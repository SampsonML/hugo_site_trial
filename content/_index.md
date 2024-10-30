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
        url: uploads/SampsonMattNovCV.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: pyramid.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: true

  - block: collection
    id: papers
    content:
      title: Recent publications
      text: ""
      filters:
        folders:
          - publication
      count: 6
    design:
      view: card
      columns: '2'
---
