---
title: "Seriously Matt"
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/splash/3sunshots.JPG
  actions:
    - label: "Blog"
      url: "/blog/"
excerpt: "Time to jump in."
intro: 
  - excerpt: '"You should make your choices as though you were choosing on behalf of the whole humanity, taking the entire burden of responsibility for how the human race behaves."'
feature_row:
  - image_path: /assets/splash/feat1-3.jpg
    title: "Total Eclipse of the Sun"
    excerpt: "These images are amazing."
    url: "/trips/eclipse/"
    btn_label: "See More"
    btn_class: "btn--primary"
  - image_path: /assets/splash/feat1-1.jpg
    title: "Biking and Bike Repair"
    excerpt: "Read the latest post."
    url: /hobbies/bikeoverhaul2/
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/img/20240113_rats4.JPG
    title: "Farewell Dear Friends"
    excerpt: "Read about our Rats."
    url: "/obituary/ohrats/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row_left:
  - image_path: /assets/splash/feat2.JPG
    title: "Weird and Wacky"
    excerpt: "There is nothing more to read yet."
    url: "#test-link"
    btn_label: "Read More Later"
    btn_class: "btn--primary"
feature_row_right:
  - image_path: /assets/splash/feat3.jpg
    title: "Matt Hobbies"
    excerpt: "There is nothing more to read yet."
    url: "#test-link"
    btn_label: "Read More Later"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}
{% include feature_row id="feature_row" %}
{% include feature_row id="feature_row_left" type="left" %}
{% include feature_row id="feature_row_right" type="right" %}