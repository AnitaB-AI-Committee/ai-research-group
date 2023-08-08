---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        AnitaB AI Committee
      image:
        filename: welcome.jpg
      text: |
        <br>

        The AnitaB AI Committee guided by AnitaB.org oversees the program to develop thought leadership on the practical use as well as ethical implications of advances in artificial intelligence and explore ways to encourage women to be active participants in the AI community. Work with the other committees to enhance the value to the AnitaB members. Provide AI expertise at AnitaB events as needed.

        At AIC, our mission is to  nurture more women  to pursue the path of AI with an aim to build inclusive and responsible AI products

  
  - block: collection
    content:
      title: Latest Posts
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
        {{% cta cta_link="./people/" cta_text="Meet the Committee →" %}}
    design:
      columns: '1'
---