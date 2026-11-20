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
        filename: Logo.jpg
      text: |
        <br>

        The **Gumuscu Research Group** has been advancing applied Artificial Intelligence research, teaching and practice at Harran University since 2018, with a focus on health, agriculture and energy.

  - block: collection
    id: latest-publications
    content:
      title: Latest Publications
      count: 3
      filters:
        folders:
          - publication
      order: desc
    design:
      view: showcase
      flip_alt_rows: false
      columns: '1'

  - block: collection
    id: latest-news
    content:
      title: Latest News
      count: 3
      filters:
        folders:
          - post
      order: desc
    design:
      view: showcase
      flip_alt_rows: false
      columns: '1'
---
