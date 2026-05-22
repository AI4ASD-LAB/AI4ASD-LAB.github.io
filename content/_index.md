---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
view: compact

sections:
  - block:
    content:
      title:
      text: 
        <br>
       Welcome to the **Field Autonomous System and Computing Lab (FAST Lab)** of Zhejiang University. Our mission is to create fully intelligent robot teams that are capable of operating in complex and diverse environments to tackle real-world challenges. We are fascinated by novel robotic concepts and excited about pushing the boundaries of robotics' potential to demonstrate remarkable capabilities. More specifically, our research interests cover multi-robot cooperation, novel robot platforms, and autonomous navigation.
      design:
        view: card
        columns: '1'

        
  - block: collection
    content:
      title: Latest News
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
      columns: '2'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen


  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
