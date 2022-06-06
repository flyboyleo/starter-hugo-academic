---
# An instance of the Contact widget.
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: 联系方式
subtitle:

content:
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

  # Contact details (edit or remove options as required)
  邮箱: wanxin@sztu.edu.cn
  电话: 18320944327
  地址:
    街道: 兰田路3002号
    城市: 广东省深圳市
    区域: 坪山区
    邮政编码: '518118'
  工作时间:
    - '工作日 10:00 to 17:20'
    - '周末 自由安排'
  
  contact_links:
    - icon: twitter
      icon_pack: fab
      name: DM Me
      link: 'https://twitter.com/Twitter'
    - icon: video
      icon_pack: fas
      name: Zoom Me
      link: 'https://zoom.com'

design:
  columns: '2'
---
