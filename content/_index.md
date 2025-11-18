---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the group
        content: Take a look at what we're working on...
        align: center
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Computational Interactive System (CIS) Lab
        content: 'Join us and shape the future of interactive AI!'
        align: center
        background:
          image:
            filename: member1.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../bio-responsive/contact/
      - title: "ITRC Talent Cultivation Conference 🏆"
        content: "Award Winner at the ITRC Talent Cultivation Conference"
        align: left
        background:
          image:
            filename: award01.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '1000px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 6000

  - block: hero
    content:
      title: |
        Computational Interactive System
      image:
        filename: research/aloha.png
      text: |
        <br>
        
        The **Computational Interactive System (CIS)** Laboratory at Dankook University conducts cutting-edge research in accessible AI technologies, including assistive robotics, sign language generation, and computer vision, with the goal of enhancing human computer interaction and improving accessibility for people with disabilities.

  - block: collection
    content:
      title: Lab New & Updates
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
      
# Latest Preprints
  - block: collection
    content:
      title: Latest Published Papers
      text: ""
      count: 3
      filters:
        folders:
          - publication
        publication_type: ''
    design:
      view: card # citation
      columns: '1'

  
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen




# Meet the team button
#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
#        
#    design:
#      columns: '1'
---
