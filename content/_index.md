---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-05-24
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
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: white
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  
  - block: collection
    id: publications
    content:
      title: My research
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
 ---
---
widget: about
active: true
weight: 1
title: About Me
body: >
  I am a PhD student at the Southern University of Science and Technology working on soft electronics, 3D printing, and adaptive displays.

education:
  - degree: PhD, Intelligent Manufacturing and Robotics
    institution: Southern University of Science and Technology
    year: 2021–2025
  - degree: B.S. & M.S., Materials Science and Engineering
    institution: Zhengzhou University
    year: 2013–2019

work:
  - role: Research Assistant
    institution: Southern University of Science and Technology
    year: 2019–2021

interests:
  - Soft Electronics
  - 3D Printing
  - Adaptive Display
  - Soft Robotics
---
