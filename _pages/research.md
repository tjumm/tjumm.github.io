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

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-sm-8 clearfix">
  <h4>{{ member.title }}</h4>
  <i>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</i>
  <ul style="overflow: hidden"></ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}
{% endfor %}
{% assign even_odd = number_printed | modulo: 2 %}

### 2. Vision-to-Language: Understanding and Reasoning

{% assign number_printed = 0 %}
{% for member in site.data.vis2lan %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-sm-8 clearfix">
  <h4>{{ member.title }}</h4>
  <i>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</i>
  <ul style="overflow: hidden"></ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}
{% endfor %}
{% assign even_odd = number_printed | modulo: 2 %}

### 3. Adversarial Vision and Robustness: Towards AI Security

{% assign number_printed = 0 %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/CurlsandWhey.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-sm-8 clearfix">
  <h4>1 Curls & Whey: Boosting Black-Box Adversarial Attacks</h4>
  <i>Yucheng Shi, Siyu Wang, Yahong Han <br>CVPR 2019, (Oral),<a href='https://openaccess.thecvf.com/content_CVPR_2019/html/Shi_Curls__Whey_Boosting_Black-Box_Adversarial_Attacks_CVPR_2019_paper.html'>(Paper)</a>, <a href='https://github.com/walegahaha/Curls-Whey'>(Project Page)</a> <br> <b> Fourth place in both </b> <a href='https://www.crowdai.org/challenges/nips-2018-adversarial-vision-challenge-untargeted-attack-track/leaderboards'>Untargeted Attack Track</a><b> and </b> <a href='https://www.crowdai.org/challenges/nips-2018-adversarial-vision-challenge-targeted-attack-track/leaderboards'>Targeted Attack Track</a> <b>of NIPS 2018 Adversarial Vision Challenge </b> <br>In this work, we propose Curls & Whey black-box attack to fix the above two defects. During Curls iteration, by combining gradient ascent and descent, we ‘curl’ up iterative trajectories to integrate more diversity and transferability into adversarial examples. Curls iteration also alleviates the diminishing marginal effect in existing iterative attacks. The Whey optimization further squeezes the ‘whey’ of noises by exploiting the robustness of adversarial perturbation. Extensive experiments on Imagenet and Tiny-Imagenet demonstrate that our approach achieves impressive decrease on noise magnitude in l2 norm. Curls & Whey attack also shows promising transferability against ensemble models as well as adversarially trained models. In addition, we extend our attack to the targeted misclassification, effectively reducing the difficulty of targeted attacks under black-box condition.</i>
  <ul style="overflow: hidden"></ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}


{% for member in site.data.adv_vision %}
{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-sm-8 clearfix">
  <h4>{{ member.title }}</h4>
  <i>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</i>
  <ul style="overflow: hidden"></ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}
{% endfor %}


{% assign even_odd = number_printed | modulo: 2 %}


