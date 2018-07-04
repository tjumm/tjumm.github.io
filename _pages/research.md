---
title: "Allan Lab - Research"
layout: textlay
excerpt: "Allan Lab -- Research"
sitemap: false
permalink: /research/
---

# Research

Our mainly foucus is on cross-media analysis for video such as video captioning, visual question answering and the new research topic about adversarial machine learning.

<b> 1. Adversarial Machine Learning </b>

Adversarial machine learning is a new research direction of our laboratory. This is a crossing research field between machine learning and computer security. The main goal is to propose more powerful and targeted attack against existing machine learning model, like image classifiers based on deep neural networks.

![]({{ site.url }}{{ site.baseurl }}/images/respic/adv.jpg){: style="width: 350px; float: right; border: 10px"}

Adversarial attacks can be divided into white-box attack and black-box attack based on attackers’ knowledge of the target model. As for white-box attack, the attacker can gain complete knowledge of target model, including its training images, optimization algorithm, and parameters of each layer in the network. When the attacker can not access the internal structure or training images, the target model can only be regarded as a black box. In this case, the attacker can only acquire information about the target model by querying.

At present, our laboratory has two publications in the field of adversarial machine learning:<i>《Schmidt: Image Augmentation for Black-box Adversarial Attack》</i>that proposed an image augmentation method better probes decision boundaries of the black-box model.<i>《Universal Perturbation Generation for Black-box Attack Using Evolutionary Algorithms》</i> that achieves source/target misclassification, black-box attack and universal perturbation by employing improved evolutionary algorithms

<b> 2. Visual Question Answering </b>

VQA is a task that given a picture or video and a corresponding natural language question, model can generate the answer automatically. It is a multi-media task which combines the technique of Natural Language Processing(NLP) and Computer Vision(CV). It has received much attention from researchers and scholars in recent years. Solving this task is a crucial step towards Artificial Intelligence.

![]({{ site.url }}{{ site.baseurl }}/images/respic/qa.jpg){: style="width: 300px; float: left; border: 10px"}

VQA can be divided into two categories in terms of the visual content: Image Question Answering(ImageQA) and Video Question Answering(VideoQA). As the natural extension of images, videos contain richer information with additional temporal and dynamic characteristics, which brings up more challenges and difficulties. The main aspect that our lab focuses on is how to combine the reasoning and knowledge to solve the VideoQA. When answering the complex question, human usually reason about the visual and language or combine the additional knowledge. So if we can let models to achieve such abilities, they will more intelligent.



The existing achievements of this topic of our lab include:
<i>《Movie Question Answering: Remembering the Textual Cues for Layered Visual Contents》(AAAI).</i>This work contributes a Layered Memory Network (LMN) to solve the MovieQA, which represents frame-level and clip-level movie content by the Static Word Memory module and the Dynamic Subtitle Memory module, respectively.
<i>《Explore Multi-step Reasoning in Video Question Answering》(ACMMM). </i>This work explores multi-step reasoning in VideoQA by formulating it as a new task, which targets to answer compositional logical structured questions bases on videos. The work contributes in developing a system to automatically generate a large-scale VideoQA dataset and proposing a novel model which combines spatial and temporal attention to address this task. 


<b> 3. Video Captioning </b>
