---
title: "Welcome to my site"
layout: splash
permalink: /welcome/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/unsplash.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
  
intro:
  - excerpt: 'Welcome! In this page you will find all my cybersecurity journy and private investigation I perform. Feel free to get in touch through my social media'


feature_row2:
  - image_path: /assets/CV-unsplash.jpg
    alt: "Review post"
    title: "Posts"
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
    excerpt: 'Review all the posts in this website, goign from posts about malware analysis to HackTheBox challenges and more'
    url: "#test-link"
    btn_label: "Go to posts"
    btn_class: "btn--primary"
    
feature_row3:
  - image_path: /assets/CV-unsplash.jpg
    alt: "CV"
    title: "Curriculum Vitae"
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
    excerpt: 'Here you can download my CV/Resume and review it'
    url: "#test-link"
    btn_label: "Download"
    btn_class: "btn--primary"

---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

