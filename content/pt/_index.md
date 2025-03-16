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
        text: Baixar CV
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
      title: '📚 Meus Estudos'
      subtitle: ''
      text: |-
           O que estou aprendendo agora?👀

           Atualmente estou focada em:

            ▫️ Aprofundar meu conhecimento em Python.

            ▫️ Explorar estruturas e ferramentas para desenvolvimento de backend.

            ▫️ Melhorar minhas habilidades em Git e colaboração em equipe.

            ▫️ Domínio de SQL com foco no MySQL Server da Oracle para gerenciamento e manipulação de banco de dados.

            ▫️ Explorar a Oracle Cloud Infrastructure (OCI) para soluções de nuvem e infraestrutura escalável.

            ▫️ Estudar IA Generativa e suas aplicações em projetos inovadores.

            <b> Entre em contato para colaborar 🚀</b>
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publicações em destaque
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 3
  
 
  
 
---
