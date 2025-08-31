---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |

      image:
        filename: welcome.jpg

      text: |
        <div style="font-family: 'Times New Roman', serif; font-size:22px;">


          <p style="text-align: justify;">
            Our lab is dedicated to uncovering macromolecular architectures and elucidating their molecular mechanisms by integrating Artificial Intelligence (AI), cell biology, and advanced cryo-electron microscopy (cryo-EM). As an interdisciplinary research team, we focus on cellular structural biology, particularly membrane remodeling processes and higher-order protein assemblies.
          </p>

          <p style="text-align: justify;">
            We embrace any technology that advances our understanding of cellular structures and are keen on developing novel cryo-EM methodologies when existing tools fall short.
          </p>

          <p style="text-align: justify;">
            Explore our research and reach out to us at SBS, HKU!
          </p>
        </div>


      
  
  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename:  coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: News
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
