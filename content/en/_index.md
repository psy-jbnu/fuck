---
title: 
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your profile text from `authors/admin/_index.md`?
      text: |
        I am an undergraduate majoring in Crop Science and Biotechnology at JBNU. I am also majoring in Computer Science and Artificial Intelligence.
        I want to learn faithfully in both fields and work in the field I want.
  - block: slider
    content:
      slides:
        - title: Welcome to my homepage!
          content: It is chance to find out....
          align: center
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: books.jpg
              filters:
                brightness: 0.7
            position: right
            color: '#666'
        - title: Crop Science and Biotechnology
          content: 'I am interested in breeding.'
          align: left
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: wheat.jpg
              filters:
                brightness: 0.7
            position: center
            color: '#555'
        - title: Crop Science and Biotechnology
          content: 'I am interested in AI.'
          align: right
          background:
            image:
              # Specify an image from `assets/media/`
              # or delete the image section to remove it
              filename: ai.jpg
              filters:
                brightness: 0.5
            position: center
            color: '#333'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      # Make the slides full screen within the browser window?
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2000 
  - block: collection
    id: posts
    content:
      title: Recent Project
      subtitle: ''
      text: 'Check my recent project'
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        # The folders to display content from
        folders:
          - projects
        author: ""
        category: ""
        tag: ""
        publication_type: ""
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      # Choose how many pages you would like to offset by
      # Useful if you wish to show the first item in the Featured widget
      offset: 0
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
    design:
      # Choose a listing view
      view: compact
      # Choose single or dual column layout
      columns: '1'
---
