---
layout: home
permalink: "/"
title: "Forest Mushroom Growers Association"
description: "Advance is a multi-purpose premium Jekyll theme. Modern design, clean code and highly configurable."
header_transparent: true
meta_title: FMGA | Forest Mushroom Growers Association

hero:
  enabled: true
  heading: "Forest Mushroom  Growers Association"
  sub_heading: "Dedicated to sustainable practices and delicious produce, <br>FMGA is revolutionizing mushroom cultivation. "
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: false #was true
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
  heading: "What We Do" #was "Our Services"
  sub_heading: ""
  limit: 6
  sort: "weight" # 'date'
  view_more_button_text: "View All Services"
  view_more_button_link: "/services"
  prevent_click: false

intro:
  enabled: true
  align: left
  image: "/assets/images/gen/content/placeholder.webp" #convert to webp, replace w/ some other photo future related
  heading: "We're the future of sustainable <br>mushroom cultivation"
  sub_heading: "Our methods enable us to produce top quality product at an affordable price."
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
      - text: "About Us"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: false # was true
  limit: 5
  sort: "weight" # 'date'

projects:
  enabled: false # was true
  heading: "Our Projects"
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
  heading: FMGA
  sub_heading: "Let us know how we can help you."
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
  enabled: false # was true
  heading: "Latest Posts"
  sub_heading: ""
  limit: 3
  columns: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Posts"
  view_more_button_link: "/blog"
  prevent_click: false
---
