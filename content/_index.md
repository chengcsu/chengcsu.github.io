---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '5rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
        skills: 'Technical Skills'
        hobbies: 'Fun'
        languages: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: xl # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
 
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My current research focuses on developing automated algorithms for individual animal identification that minimize human involvement while maintaining high reliability, leveraging clustering, verification, and human-in-the-loop supervision. In particular, I work with small-scale, real-world, unlabeled camera trap image sets of African leopards.
    
        More broadly, I am passionate about applying machine learning and computer vision to diverse image-pattern recognition challenges, including wildlife conservation, person identification, and medical image analysis. I aim to bridge advanced AI techniques with real-world problems, creating tools that enable scientists and practitioners to make data-driven decisions with greater efficiency and accuracy.

        Outside of research, I share insights through academic publications, conference presentations, and collaborative projects. I am always open to connecting with researchers and practitioners interested in conservation technology and applied AI. Please feel free to reach out if you would like to collaborate.😃 
    
#    design:
#      columns: '1'
#  - block: collection
#    id: papers
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publications
#        featured_only: true
#    design:
#     # view: article-grid
#      view: card
#      columns: 1
#  - block: collection
#    content:
#      title: Recent Publications
#      text: ''
#      filters:
#        folders:
#          - publications
#        exclude_featured: true
#    design:
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - events
#    design:
#     view: card

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 0
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      columns: 2
      # Choose a layout view
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
