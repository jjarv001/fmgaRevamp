---
layout: list
title: Services
description: "      "
permalink: "/services/"
header_transparent: true

hero:
  enabled: true
  heading: "Our Services"
  sub_heading: Whether your're lookin' for produce or lookin' to produce, we've got you covered
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: false
  background_image: "/assets/images/gen/home/mushroomsOnRightBackground.webp"
  style: "background-position: center;" # Inline style to raise the image by 200px
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"


  fullscreen_mobile: false
  fullscreen_desktop: false
  height: "700px" #orig was 500
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
  enabled: false
  align: left
  image: false
  heading: "A Full Service Agency"
  sub_heading: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sapien in elit semper accumsan. Pellentesque accumsan ut tortor eu varius. Sed id tincidunt massa, ut egestas orci."
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
  heading: "Want to learn more?"
  sub_heading: "Contact us today!"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/contact"
        external: false
        fa_icon: false
        size: normal
---
