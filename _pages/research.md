---
title: "MM Group - Research"
layout: research
excerpt: "MM Group -- Research"
sitemap: false
permalink: /research/
---

# Overview

Our research interests mainly include multimedia analysis and computing, computer vision, machine learning, and artificial intelligence. Recently, we are focusing on the visual understanding via deep learning, e.g., video/image recognition, detection and segmentation, video/image captioning, and video/image question answering (QA). We also explore the deep learning methods’ vulnerability and its robustness to adversarial attacks. Our goal is to further understand the vulnerability and interpretability of deep learning methods, which will provide theoretic evidences and methodology strategies for constructing a safer and more reliable system of image semantic understanding.

# Highlights

### 1. Object Dectection in Practical Scenes: Domain Adaptation and Few Samples



{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/pdoc.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>1 Prompt-Driven Dynamic Object-Centric Learning for Single Domain Generalization</b></h5>
  <p>Deng Li, Aming Wu, Yaowei Wang, Yahong Han<br>CVPR 2024, <a href='http://arxiv.org/abs/2402.18447'>(Preprint)</a>, <a href='https://github.com/Daniel00008/PDOC'>(Project Page)</a> <br>In this paper, we propose a dynamic object-centric perception network based on prompt learning, aiming to adapt to the variations in image complexity. Specifically, we propose an object-centric gating module based on prompt learning to focus attention on the object-centric features guided by the various scene prompts. Then, with the object-centric gating masks, the dynamic selective module dynamically selects highly correlated feature regions in both spatial and channel dimensions enabling the model to adaptively perceive object-centric relevant features, thereby enhancing the generalization capability. Experimental results on single-domain generalization tasks in image classification and object detection demonstrate the effectiveness and versatility of our proposed method.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/iiod_result2.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>2 Instance-Invariant Domain Adaptive Object Detection via Progressive Disentanglement</b></h5>
  <p>Aming Wu, Yahong Han, Linchao Zhu, Yi Yang<br>IEEE TPAMI, DOI:10.1109/TPAMI.2021.3060446, <a href='https://ieeexplore.ieee.org/abstract/document/9362301'>(Paper)</a>, <a href='https://github.com/AmingWu/IIOD'>(Project Page)</a> <br>In this work, a progressive disentangled framework is  proposed to solve domain adaptive object detection for the first time. Particularly, base on disentangled learning used for feature decomposition, we devise two disentangled layers to decompose domain-invariant and domain-specific features. And the instance-invariant features are extracted based on the domain-invariant features. Finally, to enhance the disentanglement, a three-stage training mechanism including multiple loss functions is devised to optimize our model. The proposed method can achieve excellent detection performance in night and fog domain adaptive object detection in real road scenes under different weather conditions.</p>
  <ul style="overflow: hidden"></ul>
</div>

{% for member in site.data.object_det %}


{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>{{ member.title }}</b></h5>
  <p>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</p>
  <ul style="overflow: hidden"></ul>
</div>


{% endfor %}


### 2. Adversarial Vision and Robustness: Towards AI Security


{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/CISA.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>1 Query-efficient Black-box Adversarial Attack with Customized Iteration and Sampling</b></h5>
  <p>Yucheng Shi, Yahong Han, Qinghua Hu, Yi Yang, Qi Tian <br>IEEE TPAMI, DOI:10.1109/TPAMI.2022.3169802, <a href='https://shiyuchengtju.github.io'>(Project Page)</a> <br>In this work, a new framework bridging transfer-based and decision-based attacks is proposed for query-efficient black-box adversarial attack. We reveal the relationship between current noise and variance of sampling, the monotonicity of noise compression in decision-based attack, as well as the influence of transition function on the convergence of decision-based attack. Guided by the new framework and theoretical analysis, we propose a black-box adversarial attack named Customized Iteration and Sampling Attack (CISA). CISA estimates the distance from nearby decision boundary to set the stepsize, and uses a dual-direction iterative trajectory to find the intermediate adversarial example. Based on the intermediate adversarial example, CISA conducts customized sampling according to the noise sensitivity of each pixel to further compress noise, and relaxes the state transition function to achieve higher query efficiency.</p>
  <ul style="overflow: hidden"></ul>
</div>


{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/CurlsandWhey.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>2 Curls & Whey: Boosting Black-Box Adversarial Attacks</b></h5>
  <p>Yucheng Shi, Siyu Wang, Yahong Han <br>CVPR 2019, (Oral),<a href='https://openaccess.thecvf.com/content_CVPR_2019/html/Shi_Curls__Whey_Boosting_Black-Box_Adversarial_Attacks_CVPR_2019_paper.html'>(Paper)</a>, <a href='https://github.com/walegahaha/Curls-Whey'>(Project Page)</a> <br> <b> Fourth place in both </b> <a href='https://www.crowdai.org/challenges/nips-2018-adversarial-vision-challenge-untargeted-attack-track/leaderboards'>Untargeted Attack Track</a><b> and </b> <a href='https://www.crowdai.org/challenges/nips-2018-adversarial-vision-challenge-targeted-attack-track/leaderboards'>Targeted Attack Track</a> <b>of NIPS 2018 Adversarial Vision Challenge </b> <br>In this work, we propose Curls & Whey black-box attack to fix the above two defects. During Curls iteration, by combining gradient ascent and descent, we ‘curl’ up iterative trajectories to integrate more diversity and transferability into adversarial examples. Curls iteration also alleviates the diminishing marginal effect in existing iterative attacks. The Whey optimization further squeezes the ‘whey’ of noises by exploiting the robustness of adversarial perturbation. Extensive experiments on Imagenet and Tiny-Imagenet demonstrate that our approach achieves impressive decrease on noise magnitude in l2 norm. Curls & Whey attack also shows promising transferability against ensemble models as well as adversarially trained models. In addition, we extend our attack to the targeted misclassification, effectively reducing the difficulty of targeted attacks under black-box condition.</p>
  <ul style="overflow: hidden"></ul>
</div>



{% for member in site.data.adv_vision %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>{{ member.title }}</b></h5>
  <p>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</p>
  <ul style="overflow: hidden"></ul>
</div>

{% endfor %}


### 3. Vision-to-Language: Understanding and Reasoning



{% for member in site.data.vis2lan %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/video_cap/{{ member.photo }}" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>{{ member.title }}</b></h5>
  <p>{{ member.author }}<br>{{ member.publish }} <br>{{ member.abstract }}</p>
  <ul style="overflow: hidden"></ul>
</div>

{% endfor %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/video_cap/mqa.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>3 Movie Question Answering: Remembering the Textual Cues for Layered Visual Contents</b></h5>
  <p>Bo Wang, Youjiang Xu, Yahong Han, Richang Hong<br>AAAI 2018, <a href='https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/viewPaper/16359'>(Paper)</a>, <a href='https://github.com/bowong/Layered-Memory-Network'>(Project Page)</a> <br><a href='http://movieqa.cs.toronto.edu/workshops/iccv2017/'>Winner of the MovieQA and The Large Scale Movie Description Challenge (LSMDC) @ ICCV 2017</a> <br> Understanding movie stories through only visual content is still a hard problem. In this paper, for answering questions about movies, we put forward a Layered Memory Network (LMN) that represents frame-level and clip-level movie content by the Static Word Memory module and the Dynamic Subtitle Memory module, respectively. Particularly, we firstly extract words and sentences from the training movie subtitles. Then the hierarchically formed movie representations, which are learned from LMN, not only encode the correspondence between words and visual content inside frames, but also encode the temporal alignment between sentences and frames inside movie clips. We also extend our LMN model into three variant frameworks to illustrate the good extendable capabilities. The good performance successfully demonstrates that the proposed framework of LMN is effective and the hierarchically formed movie representations have good potential for the applications of movie question answering.</p>
  <ul style="overflow: hidden"></ul>
</div>

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/video_cap/ccn.png" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>4 Connective Cognition Network for Directional Visual Commonsense Reasoning</b></h5>
  <p>Aming Wu, Linchao Zhu, Yahong Han, Yi Yang<br>NeurIPS 2019,<a href='https://openreview.net/forum?id=rJeVcVHx8H'>(Paper)</a>, <a href='https://github.com/AmingWu/CCN'>(Project Page)</a> <br>Recent studies on neuroscience have suggested that brain function or cognition can be described as a global and dynamic integration of local neuronal connectivity, which is context-sensitive to specific cognition tasks. Inspired by this idea, towards Visual commonsense reasoning (VCR), we propose a connective cognition network (CCN) to dynamically reorganize the visual neuron connectivity that is contextualized by the meaning of questions and answers. Concretely, we first develop visual neuron connectivity to fully model correlations of visual content. Then, a contextualization process is introduced to fuse the sentence representation with that of visual neurons. Finally, based on the output of contextualized connectivity, we propose directional connectivity to infer answers or rationales. Experimental results on the VCR dataset demonstrate the effectiveness of our method.</p>
  <ul style="overflow: hidden"></ul>
</div>







