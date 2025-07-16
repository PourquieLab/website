---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to our lab website!
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The Pourquié laboratory is a world leader in vertebrate musculo-skeletal axis development, lead by [Olivier Pourquié](https://www.hsci.harvard.edu/people/olivier-pourqui%C3%A9-phd).
        We are interested in the development of the vertebrate musculo-skeletal axis. Using chicken and mouse embryos as model systems, we combine developmental biology and genomic approaches to study patterning and differentiation of the precursors of muscles and vertebrae.
  

  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: hms_logo.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: Latest papers
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
