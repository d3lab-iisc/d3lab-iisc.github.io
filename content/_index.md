---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        D<sup>3</sup> Lab | IISc
      image:
        filename: d3.png
      text: |
        <br>

        The **Dynamics, Data and Design (D<sup>3</sup>) Lab** is located in the Dept. of [Mechanical Engineering](https://mecheng.iisc.ac.in/) at IISc Bengaluru and led by {{% mention "admin" %}}.

        The lab focuses on leveraging state-of-the-art machine learning techniques and experimental methods to characterize novel materials to enable the optimized design of better structures and products.
       
  # - block: markdown
  #   content:
  #     title: Announcement 📌
  #     subtitle:
  #     text: |
  #       We're looking for motivated **Project Associates/Junior Research fellows**! Get in touch if you're interested. {{% cta cta_link="uploads/advt_jrf_pa.pdf" cta_text="PA/JRF Advertisement →" cta_new_tab="true" %}}
  #   design:
  #     columns: '1'
  
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
      view: showcase
      columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
