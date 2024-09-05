---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: collection
    id: featured1
    content:
      title: Journal Articles
      filters:
        folders:
          - journal-article
        featured_only: true
    design:
      columns: '2'
      view: card
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
  - block: collection
    id: featured2
    content:
      title: Conference Papers
      filters:
        folders:
          - conference-paper
#        featured_only: true
    design:
      columns: '2'
      view: card
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']
     padding: ['20px', '0', '20px', '0']
---
