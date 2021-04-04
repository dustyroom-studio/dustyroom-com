---
title: "Projects"
layout: splash
permalink: /splash
feature_row:
  - image_path: assets/images/empty-1.png
    alt: "placeholder image 1"
    title: "Empty."
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/empty"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/flat-kit-header-1.jpeg
    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Flat Kit"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/flat-kit"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/statickit-tapemachine-header-1.jpeg
    title: "Static Kit"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "/static-kit"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/sparvagn-1.jpeg
    alt: "placeholder image 2"
    title: "Spårvagn"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "/sparvagn"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/soundmarine-1.png
    alt: "placeholder image 2"
    title: "Soundmarine"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "/soundmarine"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/powernode-1.webp
    alt: "placeholder image 2"
    title: "Powernode"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "/powernode"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}