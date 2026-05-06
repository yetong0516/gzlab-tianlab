---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        广州实验室
        田鲁亦课题组
      image:
        filename: welcome.jpg
      text: |
        <br>

        **田鲁亦课题组**依托广州实验室，专注于单细胞组学、空间组学与纳米孔测序新技术及数据分析算法的开发，致力于解析免疫系统的时空调控机制及其在呼吸系统疾病中的作用。课题组于2022年11月正式成立。

  - block: collection
    content:
      title: 最新动态
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image:
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  - block: collection
    content:
      title: 最新论文
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
        {{% cta cta_link="./people/" cta_text="认识团队 →" %}}
    design:
      columns: '1'
---
