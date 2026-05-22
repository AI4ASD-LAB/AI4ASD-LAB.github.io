---
# Leave the homepage title empty to use the site title
title:
date: 2026-5-22
type: landing
view: compact

sections:
  - block:
    content:
      title:
      text: 
        <br>
       欢迎来到 **AI for Autism** 实验室，我们的使命是推动人工智能技术在孤独症谱系障碍（ASD）领域的创新应用，打造能够理解、陪伴并辅助ASD个体的智能系统，切实回应现实世界中的教育与康复需求。我们对前沿的AI与交互技术充满热情，致力于拓展智能系统在特殊教育与人机协作中的边界，展现技术在人文关怀中的独特潜力。具体而言，我们的研究方向包括：1基于AI的ASD早期筛查与行为分析2个性化智能康复与教育干预系统3人机交互与可穿戴设备在ASD辅助中的应用4多模态数据处理与情感计算
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
