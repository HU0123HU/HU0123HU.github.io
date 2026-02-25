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

<style>
  /* 彻底禁用 Demos 版块的卡片交互与悬浮特效 */
  #demos a {
    pointer-events: none !important; /* 禁用点击动作，鼠标不会变成小手 */
  }
  #demos a:hover {
    text-decoration: none !important; /* 取消标题悬浮时的下划线 */
  }
  #demos img {
    transition: none !important; /* 关闭图片的动态过渡效果 */
    transform: none !important;  /* 禁止图片悬浮放大 */
  }
</style>
