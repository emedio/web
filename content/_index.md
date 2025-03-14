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
        filename: group.png
      text: |
          The Medium Effects research group, led by Prof. Iñaki Tuñón, is based in the Department of Physical Chemistry at the University of Valencia.
          The group focuses on the theoretical description of chemical processes in condensed phases,
          solutions, and biological environments, combining advanced theoretical methods with simulations.
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
      count: 6
      offset: 0
      order: desc
      page_type: news
      archive:
        enable: true
    design:
      view: masonry
      columns: '1'
---
