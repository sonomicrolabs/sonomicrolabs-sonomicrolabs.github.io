---
layout: list
title: Services
description: "A selection of our digital services"
permalink: /services/
permalink_en: /services/
header_transparent: true
lang: en

hero:
  enabled: true
  heading: "Services"
  sub_heading: "We offer a comprehensive, sustainable water management solutions."
  text_color: "#FFFFFF"
  background_color: false
  background_gradient: true
  background_image: "/assets/images/gen/home/home-8-large.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: false
  fullscreen_desktop: false
  height: "500px"
  buttons:
    enabled: false
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

grid:
  collection: "services"
  sort_by: "weight" # "date", "weight"
  columns: 3
  prevent_click: false

intro:
  enabled: true
  align: left
  image: false
  heading: "Sustainable Water Management Solutions for Businesses."
  sub_heading: "Our hardware and digital platform provide actionable data to optimize water use, reduce waste, and our team provides consultations to help your business achieve its sustainability goals while adhering to budget constraints. Join us in revolutionizing water management and fostering a greener future."
  buttons:
    enabled: false
    list:
      - text: "About Us"
        url: "/about/"
        external: false
        fa_icon: false
        size: normal

outro:
  enabled: true
  align: left
  image: false
  heading: "Ready to get started?"
  sub_heading: "Contact us today for a free quote!"
  buttons:
    enabled: true
    list:
      - text: "Get A Quote"
        url: "/contact"
        external: false
        fa_icon: false
        size: normal
---
{% tf _services_/services.md %}