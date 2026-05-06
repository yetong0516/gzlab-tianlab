---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: 联系我们
      text: |-
        欢迎对单细胞组学、空间组学、纳米孔测序、生物信息学及人工智能等领域感兴趣的研究者联系田鲁亦课题组。课题组长期招募副研究员、博士后及研究实习员，欢迎垂询。
      email: tian_luyi@gzlab.ac.cn
      address:
        street: 广州市黄埔区健康城
        city: 广州
        region: 广东省
        postcode: '510700'
        country: 中国
        country_code: CN
      coordinates:
        latitude: '23.1291'
        longitude: '113.2644'
      directions: 广州实验室，广东省广州市黄埔区

      # Automatically link email and phone or display as text?
      autolink: true

      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
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
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
