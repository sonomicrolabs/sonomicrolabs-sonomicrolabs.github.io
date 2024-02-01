---
layout: team-member
header_transparent: true
title: "Einar Már Björgvinsson"
date: 2023-08-16T13:44:30+10:00
weight: 3
description: "einar description"
thumbnail: "/assets/images/team/mike-vance-thumbnail.jpeg"
image: "/assets/images/team/mike-vance.jpeg"
jobtitle: "einar jobtitle"
links:
  - url: "https://www.linkedin.com/in/einar-m%C3%A1r-bj%C3%B6rgvinsson-9167833/"
    label: LinkedIn
    icon: "fab fa-linkedin"
  - #url: "https://www.linkedin.com/in/gudmundsson/"
    #label: Github
    #icon: "fab fa-github"
lang: en
hero:
  enabled: true
  heading: "Meet the Team"
  sub_heading: ""
  text_color: "#FFFFFF"
  background_color: ""
  background_gradient: true
  background_image: false
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: false
  fullscreen_desktop: false
  height: "330px"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

grid:
  collection: "team"
  sort_by: "weight" # "date", "weight"
  columns: 3
  prevent_click: false
---
{% tf _collections/team/Einar.md %}