---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Iñaki Tuñón Research Group
      text: |
        <br>
        <div style="display: flex; align-items: center;">
        <p>The research group was founded by Prof. Estanislao Silla in the Department of Physical Chemistry of the University of Valencia 
        at the beginning of the 90's. The scientific work of the group has been always focused on the theoretical description of chemical 
        processes in condensed phases: solutions and biological environments. The group is currently led by Iñaki Tuñón.</p>
        <div style="margin-left: 20px; width: 150%;">
          {{< figure src="group.jpg" alt="Research Group" lightbox="false" >}}
        </div>
        </div>
    design:
      background:
        image:
          filename: background.png
      spacing:
        padding: ['20px', '0', '20px', '0']
  
  - block: collection
    content:
      title: Research
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      page_type: research
    design:
      view: masonry
      columns: '1'

  - block: collection
    content:
      title: Latest papers
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

---
