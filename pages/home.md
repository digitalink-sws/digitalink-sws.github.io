---
layout: home
permalink: "/"
title: "Jekyll Advance"
description: "Advance is a multi-purpose premium Jekyll theme. Modern design, clean code and highly configurable."
header_transparent: true
meta_title: 智采数链 - 离散生产数字化供应链

hero:
  enabled: true
  heading: "智采数链"
  sub_heading: "可落地的离散生产数字化供应链端到端解决方案。轻量化快速部署，非入侵式业务启动咨询，专业数字化服务团队。"
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: true
  background_image: "/assets/images/gen/home/home-1-large.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: false
  height: "660px"
  buttons:
    enabled: false
    list:
      - text: "Buy Now"
        url: "https://www.zerostatic.io/theme/jekyll-advance/"
        external: true
        fa_icon: false
        size: large # "small", "normal", "large"
        outline: false
        style: "light" # "light", "dark", "primary"
      - text: "Documentation"
        url: "https://www.zerostatic.io/docs/jekyll-advance/v2.0/"
        external: true
        fa_icon: false
        size: large
        outline: true
        style: "light"

services:
  enabled: true
  heading: "我们的专业服务："
  sub_heading: ""
  limit: 4
  sort: "weight" # 'date'
  view_more_button_text: "更多服务详情…"
  view_more_button_link: "/services"
  prevent_click: false

intro:
  enabled: true
  align: left
  image: "/assets/images/gen/home/cruisor.jpg"
  heading: "助力中国首条豪华邮轮制造"
  sub_heading: "智采数链 离散生产数字化供应链解决方案，基于15年的船舶制造场景。2500万非标配件。"
  features:
    enabled: false
    list:
      - text: "Configure the homepage sections in front-matter."
        fa_icon: "fas fa-check"
      - text: "An advanced hero image section with dozens of design options."
        fa_icon: "fas fa-check"
      - text: "Fully responsive and SEO optimised."
        fa_icon: "fas fa-check"
      - text: "Multiple content types including services, projects, blog and more."
        fa_icon: "fas fa-check"
  buttons:
    enabled: true
    list:
      - text: "了解更多"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: false
  limit: 5
  sort: "weight" # 'date'

projects:
  enabled: true
  heading: "成功案例"
  sub_heading: ""
  limit: 2
  columns: 2
  sort: "weight" # 'date'
  view_more_button_text: "View All Projects"
  view_more_button_link: "/projects"
  prevent_click: false

outro:
  enabled: true
  align: center
  image: false
  heading: Get Started Today
  sub_heading: "Save time and money using this premium Jekyll theme."
  features:
    enabled: false
    list:
      - text: "Free Quote"
        fa_icon: "fas fa-envelope-open-text"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        size: "large"

posts:
  enabled: true
  heading: "Latest Posts"
  sub_heading: ""
  limit: 3
  columns: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Posts"
  view_more_button_link: "/blog"
  prevent_click: false
---
