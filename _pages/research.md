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
{% for member in site.data.object_det %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.title }}</h4>
  <li>{{ member.author }}<br><{{ member.publish }}> <br><{{ member.abstract }}> </li>
  <ul style="overflow: hidden">
  
  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}
  
  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}
  
  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}
  
  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}
  
  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


