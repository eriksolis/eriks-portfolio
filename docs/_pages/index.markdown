---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
excerpt: "Game Developer, Game Designer, and Pokémon fan."
title: " "
header:
    overlay_image: /assets/images/Pa_wallpaper_m_mangetsu_PC.jpg
    overlay_filter: 0.5
    caption: "Photo credit: **Pokémon**"
    actions:
        - label: "Head to my Projects"
          url: "/projects/"
permalink: /
intro: 
  - excerpt: Check out one of my latest games!

feature_row:
  - image_path: /assets/images/funkyfishin_teaserimage.png
    alt: "Funky Fishin' Logo"
    title: "Funky Fishin'"
    excerpt: '**VR Fishing Rhythm game** where you catch fish by swinging your controllers to the beat!'
    url: "/projects/funky-fishin/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row" type="center" %}
