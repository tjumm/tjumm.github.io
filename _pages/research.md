---
title: "MM Group - Research"
layout: textlay
excerpt: "MM Group -- Research"
sitemap: false
permalink: /research/
---

# Overview

Our research interests mainly include multimedia analysis and computing, computer vision, machine learning, and artificial intelligence. Recently, we are focusing on the visual understanding via deep learning, e.g., video/image recognition, detection and segmentation, video/image captioning, and video/image question answering (QA). We also explore the deep learning methods’ vulnerability and its robustness to adversarial attacks. Our goal is to further understand the vulnerability and interpretability of deep learning methods, which will provide theoretic evidences and methodology strategies for constructing a safer and more reliable system of image semantic understanding.

# Highlights

### 1. Object Dectection in Practical Scenes: Domain Adaptation and Few Samples

{% assign number_printed = 0 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h4>{{ member.title }}</h4>
  <i>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</i>
  <ul style="overflow: hidden"></ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% assign even_odd = number_printed | modulo: 2 %}




