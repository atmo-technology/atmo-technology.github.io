---
title: "Splash Page"
layout: splash
permalink: /splash-page/
header:
  overlay_image: /assets/images/bgimage.png
  actions:
    - label: "Join The Crowd"
      url: "https://www.crowdhaus.co.uk/#welcome"
excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
feature_row:
  - image_path: assets/images/blake-wheeler.jpg
    image_caption: "Photo by Blake Wheeler on [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/toa-heftiba.jpg
    image_caption: "Photo by Toa Heftiba on [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row2:
  - image_path: assets/images/blake-wheeler.jpg
    image_caption: "Photo by Blake Wheeler on [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/toa-heftiba.jpg
    image_caption: "Photo by Toa Heftiba on [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---


{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}