---
# Leave the homepage title empty to use the site title
title: "Constantin Venhoff"
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
    design:
      css_class: dark
      background:
        color: gray
  - block: resume-awards
    id: awards
    content:
      title: Awards
      username: admin
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
