---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing


sections:
  - block: hero
    content:
      title: You Soft Matter Group
      image:
        filename: welcome.jpg
      text: |
        <br>

        
        We are interested in the emergence in active/living matter. From cellular cytoskeleton to animal groups, these systems ubiquitously exhibit novel "microscopic" dynamics which, subsequently lead to fascinating collective behaviors. To uncover the mysteries behind these phenomena, we use theoretical modeling with the help of computer simulations. Our research is interest oriented, involving various subjects in active/living matter, e.g. bacterial colonies, active fluids and their interfaces, and systems with broken Newton's 3rd law. Go ahead and explor this site if you'd like to know more :).

  

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
      view: article-grid
      columns: '1'
  

  - block: collection
    content:
      title: Recent publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'all'
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
