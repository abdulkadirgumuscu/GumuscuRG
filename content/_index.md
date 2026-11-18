---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Gumuscu
        Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Gumuscu Research Group** has been advancing applied Artificial Intelligence research, teaching and practice at Harran University since 2018, with a focus on health, agriculture and energy. We build artificial intelligence systems that make everyday life easier, safer and more efficient. Our work takes over the heavy lifting of data analysis and monitoring, so that patients, farmers and engineers can focus on what matters most.  

The group is led by Dr. Abdülkadir Gümüşçü, Associate Professor of Electrical and Electronics Engineering at Harran University and Honorary Senior Lecturer in the Department of Bioengineering at Imperial College London. We combine machine learning, computer vision, wearable sensing and metaheuristic optimization, and we test our methods on real problems: Parkinson's disease, crop disease and planting decisions, and solar energy systems.
  
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
      columns: '1'

  - block: collection
    content:
      title: Latest Preprints
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
