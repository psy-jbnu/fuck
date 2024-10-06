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
        저는 전북대학교에서 작물생명과학과를 전공하고 있는 학부생입니다. 컴퓨터인공지능학부도 복수전공하고 있습니다.
        두 분야 모두 충실히 학습하여 제가 원하는 분야에 진출하고 싶습니다.
  - block: slider
    content:
      slides:
        - title: 제 홈페이지에 오신 것을 환영합니다!
          content: 저에 대해 알아갈 수 있는 기회입니다....
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
        - title: 작물생명과학
          content: '작물 육종에 관심이 있습니다.'
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
        - title: 컴퓨터공학
          content: 'AI에 관심이 있습니다.'
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
---
