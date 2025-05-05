---
layout: list
title: Services
description: "      "
permalink: "/services/"
header_transparent: true

hero:
  enabled: true
  heading: "Our Services"
  sub_heading: "Whether your're lookin' for produce or lookin' to produce, we've got you covered"
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: false
  background_image: "/assets/images/gen/home/mushroomsOnRightBackground.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  #how do I raise the image 200 px
  height: "1000px"
  # width: "200px"


  fullscreen_mobile: false
  fullscreen_desktop: false
  #height: "500px"
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
