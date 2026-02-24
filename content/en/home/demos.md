---
# An instance of the Featured widget for Demos/Projects.
widget: featured
active: true
headless: true

# Order that this section appears on the page. 
# 设为 25，正好排在 Research (20) 和 Publications (30) 之间
weight: 25

title: Demos & Projects
subtitle: "Fun prototypes and engineering experiments" # 如果不需要副标题可以留空: ""

content:
  # 关键修改：告诉系统去寻找名为 'demos' 的内容文件夹
  page_type: demos
  count: 0
  filters:
    author: ""
    category: ""
    publication_type: ""
    tag: ""
  order: desc

design:
  # 完美复刻 Research 版块的卡片样式和 CSS 排版
  view: research_item_card
  list_css_class: "research-list-wrap"
---
