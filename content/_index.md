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
        filename: group.jpg
      text: |
        The research group Medium Effects led by Prof. Iñaki Tuñón is 
        placed at the Department of Physical Chemistry of the University of 
        Valencia, The scientific work of the group is focused on the theoretical
        description of chemical processes in condensed phases, solution and 
        biological environments, combining theory and simulations.
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
        padding: ['20px', '0', '20px', '0']
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: news
      archive:
        enable: true
    design:
      view: masonry
      columns: '1'
---
