---
title: "MM Group - Research"
layout: textlay
excerpt: "MM Group -- Research"
sitemap: false
permalink: /research/
---

# Overview

Our research interests mainly include multimedia analysis and computing, computer vision, machine learning, and artificial intelligence. Recently, we are focusing on the visual understanding via deep learning, e.g., video/image recognition, detection and segmentation, video/image captioning, and video/image question answering (QA). We also explore the deep learning methods’ vulnerability and its robustness to adversarial attacks. Our goal is to further understand the vulnerability and interpretability of deep learning methods, which will provide theoretic evidences and methodology strategies for constructing a safer and more reliable system of image semantic understanding.

# Funding

- The Key Theories and Methods for Intelligent Cross-media Question Answering and Reasoning, NSFC Key Program, Co-PI
- The Underlying Theory Research and Visual Analysis Technology for Intelligent City Surveillance, NSFC Key Program, Co-PI
- Theories and Methods of Adversarial Machine Learning for Image Semantic Understanding, NSFC General Program, PI
- Ad Hoc Web Image Semantic Understanding with Limited Supervision, NSFC General Program, PI

# Highlights

<b> 1. Video Captioning </b>

Visual captioning targets to automatically generate natural language descriptions for images or videos, based on visual content understanding, which is regarded as a profound challenge in both computer vision and language processing communities. Generating meaningful natural language description for visual content may beneft a wide variety of applications, such as human-robot interaction, impaired people auxiliary, and video retrieval. Thus it has attracted much attention recently and intensive research interests have been paid for this topic.

![]({{ site.url }}{{ site.baseurl }}/images/respic/caption.jpg){: style="width: 350px; float: right; border: 10px"}

Early video captioning approaches attempt to detect semantic concepts (e.g., objects, subjects, and verbs) with multiple visual classifiers, and fill predicted concepts in pre-defined sentence templates for caption generation. These methods always create sentences with specifc syntactical structure, which may lose ﬂexibility of natural language and highly depend on pre-defned templates of sentence. With the rapid development of deep neural networks, especially Recurrent Neural Network (RNN), inspiring results have been achieved for video captioning. Recent RNN-based video captioning approaches have greatly enhanced the performance owning to the merits that diﬀerentiable recurrent models can directly model variable-length inputs and outputs. 

The main achievements of our lab are as follows: <i>"Multirate Multimodal Video Captioning" (ACM MM 2017 Grand Challenge 'Honorable Mention Award').</i> In MSR Video to Language Challenge of ACM MM 2017 Grand Challenge, we came second in M1 and ranked third in M2. The work proposes a Multirate Multimodal Approach for
video captioning, which incorporats visual, motion, and topic information together. <i>"Catching the Temporal Regions-of-Interest for Video Captioning" (ACMMM).</i> This work proposes a Dual Memory Recurrent Model (DMRM) to incorporate temporal structure of global features and regions-of-interest features in parallel, which will obtain rough understanding of video content and particular information of regions-of-interest. <i>"Sequential Video VLAD: Training the Aggregation Locally and Temporally" (IEEE T-IP).</i> This work develop a novel Sequential VLAD layer, named SeqVLAD, to combine a trainable VLAD encoding process and the RCNs architecture into a whole framework for both video captioning and video action recognition. <i>"Spoting and Aggregating Salient Regions for Video Captioning" (ACMMM).</i> This work automatically spots salient regions in each video frame and simultaneously learn a discriminative spatio-temporal representation for video captioning.

<b> 2. Visual Question Answering </b>

VQA is a task that given a picture or video and a corresponding natural language question, model can generate the answer automatically. It is a multi-media task which combines the technique of Natural Language Processing(NLP) and Computer Vision(CV). It has received much attention from researchers and scholars in recent years. Solving this task is a crucial step towards Artificial Intelligence.

![]({{ site.url }}{{ site.baseurl }}/images/respic/qa.jpg){: style="width: 300px; float: left; border: 10px"}

VQA can be divided into two categories in terms of the visual content: Image Question Answering(ImageQA) and Video Question Answering(VideoQA). As the natural extension of images, videos contain richer information with additional temporal and dynamic characteristics, which brings up more challenges and difficulties. The main aspect that our lab focuses on is how to combine the reasoning and knowledge to solve the VideoQA. When answering the complex question, human usually reason about the visual and language or combine the additional knowledge. So if we can let models to achieve such abilities, they will more intelligent.

The existing achievements of this topic of our lab include:
<i>"Movie Question Answering: Remembering the Textual Cues for Layered Visual Contents" (AAAI).</i>This work contributes a Layered Memory Network (LMN) to solve the MovieQA, which represents frame-level and clip-level movie content by the Static Word Memory module and the Dynamic Subtitle Memory module, respectively.
<i>"Explore Multi-step Reasoning in Video Question Answering" (ACMMM). </i>This work explores multi-step reasoning in VideoQA by formulating it as a new task, which targets to answer compositional logical structured questions bases on videos. The work contributes in developing a system to automatically generate a large-scale VideoQA dataset and proposing a novel model which combines spatial and temporal attention to address this task. 

<b> 3. Adversarial Machine Learning </b>

Adversarial machine learning is a new research direction of our laboratory. This is a crossing research field between machine learning and computer security. The main goal is to propose more powerful and targeted attack against existing machine learning model, like image classifiers based on deep neural networks.

![]({{ site.url }}{{ site.baseurl }}/images/respic/adv.jpg){: style="width: 350px; float: right; border: 10px"}

Adversarial attacks can be divided into white-box attack and black-box attack based on attackers’ knowledge of the target model. As for white-box attack, the attacker can gain complete knowledge of target model, including its training images, optimization algorithm, and parameters of each layer in the network. When the attacker can not access the internal structure or training images, the target model can only be regarded as a black box. In this case, the attacker can only acquire information about the target model by querying.

At present, our laboratory has two publications in the field of adversarial machine learning:<i> "Schmidt: Image Augmentation for Black-box Adversarial Attack"</i> that proposed an image augmentation method better probes decision boundaries of the black-box model. <i>"Universal Perturbation Generation for Black-box Attack Using Evolutionary Algorithms"</i> that achieves source/target misclassification, black-box attack and universal perturbation by employing improved evolutionary algorithms