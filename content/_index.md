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
        text: cv
        url: uploads/SampsonMattNovCV.pdf
      button:
        text: github
        url: https://github.com/SampsonML
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: cubp.svg
          filters:
            brightness: 0.01
          size: cover
          position: center
          parallax: true
  
---

  #- block: collection
    id: papers
    content:
      title: recent publications
      text: ""
      filters:
        folders:
          - publication
      count: 6
    design:
      view: citation
---
