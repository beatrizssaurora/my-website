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
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
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
  - block: markdown
    content:
      title: '📚 My Studies'
      subtitle: ''
      text: |-
           What am I learning now?👀

           Currently, I am focused on:

            ▫️ Deepening my knowledge of Python for data analysis and automation.

            ▫️ Exploring frameworks and tools for backend development.

            ▫️ Improving my Git and team collaboration skills.

            ▫️ Mastering SQL with a focus on Oracle’s MySQL Server for database management and manipulation.

            ▫️ Exploring Oracle Cloud Infrastructure (OCI) for cloud solutions and scalable infrastructure.

            ▫️ Studying Generative AI and its applications in innovative projects.

            <b> Please reach out to collaborate 🚀</b>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
 
  
 
---
