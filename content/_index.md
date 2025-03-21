---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: Iñaki Tuñón Research Group
      image:
        filename: nada.png
      text: |
          The Medium Effects Research Group, led by Prof. Iñaki Tuñón, is based in the Department of Physical Chemistry at the University of Valencia. Our research delves into the theoretical characterization of chemical processes occurring in condensed phases, solutions, and biological environments, integrating advanced theoretical methodologies with computational simulations. These insights have practical applications across various fields, including drug design and enzyme catalysis.
      cta:
        label: Research
        url: research
      cta_alt:
        label: Contact
        url: contact
    design:
      background:
        image:
          filename: background.png
      spacing:
        padding: ['100px', '0', '100px', '0']
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 6
      offset: 0
      order: desc
      page_type: news
      archive:
        enable: true
    design:
      view: masonry
      columns: '1'

  - block: markdown
    content:
      title: ' '
      subtitle: 'Support and Funding'
      text:
    design:
      columns: '1' 
      background:
        image: 
          filename: financiers.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: auto
          text_color_light: true
      spacing:
        padding: ['80px', '0', '0', '0']
      css_class: fullscreen

---
