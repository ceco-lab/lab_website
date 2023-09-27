---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
       <span style="font-family: 'Roboto', sans-serif; color: white; font-size: 66px;">Computational ecology <span style="color: aliceblue; font-size: 16px; font-style: italic;">Research Group</span></span>
        
      
      text: |
        <br>
        <br>
        <br>
        <br>
        <br>
        <p><span style="font-family: 'Roboto', Times, serif; color: white; font-size: 19px;">Plant ecology, Computational biology, Metabolomic, conservation, ORD...</span></p>

    image:
      filename: #logo.jpg

    design:
        columns: '1'
        background:
          image: 
           filename: entete_group4.jpg
           filters:
             brightness: 1
          parallax: false
          position: center
          size: cover



  - block: collection
    content:
      title: |
       <span style="font-family: 'Montserrat', sans-serif; color:white; font-size: 30px;">Latest News<br></span>
      
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
      background:
        color: black

    

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: entete_group4.jpg
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