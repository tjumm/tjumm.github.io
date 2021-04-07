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

### 1. Domain Adaption

|  |  |
| --- | --- |
| ![]({{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/IIDO.png){: style="width: 350px; float: left; border: 10px"} | **Instance-Invariant Domain Adaptive Object Detection via Progressive Disentanglement** <br> Most state-of-the-art methods of object detection suffer from poor generalization ability when the training and test data are from different domains, e.g., with different styles. To address this problem, a progressive disentangled framework is first proposed to solve domain adaptive object detection. Particularly, base on disentangled learning used for feature decomposition, we devise two disentangled layers to decompose domain-invariant and domain-specific features. And the instance-invariant features are extracted based on the domain-invariant features. Finally, to enhance the disentanglement, a three-stage training mechanism including multiple loss functions is devised to optimize our model. In the experiment, we verify the effectiveness of our method on three domain-shift scenes.  |
| ![]({{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/SSDA.png){: style="width: 350px; float: left; border: 10px"} | **Bidirectional Adversarial Training for Semi-Supervised Domain Adaptation** <br> Semi-supervised domain adaptation (SSDA) is a novel branch of machine learning that scarce labeled target examples are available, compared with unsupervised domain adaptation. To make effective use of these additional data so as to bridge the domain gap, one possible way is to generate adversarial examples. However, the traditional adversarial training adds noises in arbitrary directions, which is inefficient to migrate between domains.In this work, we devise a general bidirectional adversarial training method and employ gradient to guide adversarial examples across the domain gap, i.e., the Adaptive Adversarial Training (AAT) for source to target domain and Entropypenalized Virtual Adversarial Training (E-VAT) for target to source domain. Particularly, we devise a Bidirectional Adversarial Training (BiAT) network to perform diverse adversarial trainings jointly. We evaluate the effectiveness of BiAT on three benchmark datasets and experimental results demonstrate the proposed method achieves the state-of-the-art.|


### 2. Video Captioning
![]({{ site.url }}{{ site.baseurl }}/images/respic/video_cap/MemNet.png){: style="width: 350px; float: left; border: 10px"}

<b> Hierarchical Memory Decoder for Visual Narrating </b>

The challenge of visual narrating  mainly lies in how to design a decoder to generate accurate descriptions matching visual content. In this paper, we devise a novel memory decoder for visual narrating. Concretely, to obtain a better multi-modal representation, we first design a new multi-modal fusion method to fully merge visual and lexical information. Then, based on the fusion result, during decoding, we construct a MemNet-based decoder consisting of multiple memory layers. Particularly, in each layer, we employ a memory set to store previous decoding information and utilize an attention mechanism to adaptively select the information related to the current output. Meanwhile, we also employ a memory set to store the decoding output of each memory layer at the current time step and still utilize an attention mechanism to select the related information. Experimental results show that our decoder could obtain superior results and outperform the performance of conventional RNN-based decoder.

![]({{ site.url }}{{ site.baseurl }}/images/respic/video_cap/CRVC.png){: style="width: 350px; float: left; border: 10px"}

<b> Convolutional Reconstruction-to-Sequence for Video Captioning </b>

For video captioning, the commonly used method is LSTM decoder with an attention mechanism. Although LSTM owns a memory cell to memorize history information, it is still limited to several time steps. To alleviate this problem, we propose a convolutional reconstruction-to-sequence model for video captioning. Particularly, we first append inter-frame differences to each CNN-extracted frame feature to get a more discriminative representation; then with that as the input, we encode each frame to be a more compact feature by a one-layer convolutional mapping, which could be taken as a reconstruction network. In the decoding stage, we first fuse visual and lexical feature; then we stack multiple dilated convolutional layers to form a hierarchical decoder.  Experiments on two benchmark datasets show that our method could obtain state-of-the-art performance.

![]({{ site.url }}{{ site.baseurl }}/images/respic/video_cap/VCHP.png){: style="width: 350px; float: left; border: 10px"}

<b> Video Interactive Captioning with Human Prompts </b>

As a video often includes rich visual content and semantic details, different people may be interested in different views. Thus the generated sentence always fails to meet the ad hoc expectations. In this paper, we make a new attempt that, we launch a round of interaction between a human and a captioning agent. After generating an initial caption, the agent asks for a short prompt from the human as a clue of his expectation. Then, based on the prompt, the agent could generate a more accurate caption. We name this process a new task of video interactive captioning (ViCap). Taking a video and an initial caption as input, we devise the ViCap agent which consists of a video encoder, an initial caption encoder, and a refined caption generator. Experimental results not only show the prompts can help generate more accurate captions, but also demonstrate the good performance of the proposed method. 

![]({{ site.url }}{{ site.baseurl }}/images/respic/video_cap/SASR.png){: style="width: 350px; float: left; border: 10px"}

<b> Spotting and Aggregating Salient Regions for Video Captioning </b>

This paper proposes a new framework to automatically spot salient regions in each video frame and simultaneously learn a discriminative spatio-temporal representation for video captioning. First, in a Spot Module, we automatically learn the saliency value of each location to separate salient regions from video content as the foreground and the rest as background by two operations of ‘hard separation’ and ‘soft separation’, respectively. Then, in an Aggregate Module, to aggregate the foreground/background descriptors into a discriminative spatio-temporal representation, we devise a trainable video VLAD process to learn the aggregation parameters. Finally, we utilize the attention mechanism to decode the spatio-temporal representations of different regions into video descriptions. Experiments on two benchmark datasets demonstrate our method outperforms most of the state-of-the-art methods.

### 3. Visual Question Answering

![]({{ site.url }}{{ site.baseurl }}/images/respic/vqa/RHGA.png){: style="width: 350px; float: left; border: 10px"}

<b> Reasoning with Heterogeneous Graph Alignment for Video Question Answering </b>

The dominant video question answering methods are based on fine-grained representation or model-specific attention mechanism. They usually process video and question separately, then feed the representations of different modalities into following late fusion networks. Although these methods use information of one modality to boost the other, they neglect to integrate correlations of both inter- and intra-modality in an uniform module. We propose a deep heterogeneous graph alignment network over the video shots and question words. Furthermore, we explore the network architecture from four steps: representation, fusion, alignment, and reasoning. Within our network, the inter- and intra-modality information can be aligned and interacted simultaneously over the heterogeneous graph and used for cross-modal reasoning. Experiments show the network to be superior in quality. 

![]({{ site.url }}{{ site.baseurl }}/images/respic/vqa/ccn.png){: style="width: 350px; float: left; border: 10px"}

<b> Connective Cognition Network for Directional Visual Commonsense Reasoning </b>

Recent studies on neuroscience have suggested that brain function or cognition can be described as a global and dynamic integration of local neuronal connectivity, which is context-sensitive to specific cognition tasks. Inspired by this idea, towards Visual commonsense reasoning (VCR), we propose a connective cognition network (CCN) to dynamically reorganize the visual neuron connectivity that is contextualized by the meaning of questions and answers. Concretely, we first develop visual neuron connectivity to fully model correlations of visual content. Then, a contextualization process is introduced to fuse the sentence representation with that of visual neurons. Finally, based on the output of contextualized connectivity, we propose directional connectivity to infer answers or rationales. Experimental results on the VCR dataset demonstrate the effectiveness of our method.

![]({{ site.url }}{{ site.baseurl }}/images/respic/vqa/EMSR.png){: style="width: 350px; float: left; border: 10px"}

<b> Explore Multi-Step Reasoning in Video Question Answering </b>

In this paper, we formulate multi-step reasoning in Video question answering (VideoQA) as a new task to answer compositional and logical structured questions based on video content. We design a system to automatically generate a large-scale dataset, namely SVQA (Synthetic Video Question Answering). Compared with other VideoQA datasets, SVQA contains exclusively long and structured questions with various spatial and temporal relations between objects. Towards automatic question answering in SVQA, we develop a new VideoQA model. Particularly, we construct a new attention module, which contains spatial attention mechanism to address crucial and multiple logical sub-tasks embedded in questions, as well as a refined GRU called ta-GRU (temporal-attention GRU) to capture the long-term temporal dependency and gather complete visual cues. Experimental results show the capability of multi-step reasoning of SVQA and the effectiveness of our model when compared with other existing models. 

##  4. Adversarial Machine learning 

![]({{ site.url }}{{ site.baseurl }}/images/respic/adv/PDAN.png){: style="width: 350px; float: left; border: 10px"}

<b> Polishing Decision-based Adversarial Noise with a Customized Sampling </b>

In this paper, we demonstrate the advantage of using current noise and historical queries to customize the variance and mean of sampling in boundary attack to polish adversarial noise. We further reveal the relationship between the initial noise and the compressed noise in boundary attack. We propose Customized Adversarial Boundary (CAB) attack that uses the current noise to model the sensitivity of each pixel and polish adversarial noise of each image with a customized sampling setting. On the one hand, CAB uses current noise as a prior belief to customize the multivariate normal distribution. On the other hand, CAB keeps the new samplings away from historical failed queries to avoid similar mistakes. Experimental results measured on several image classification datasets emphasizes the validity of our method. 

![]({{ site.url }}{{ site.baseurl }}/images/respic/adv/aia.png){: style="width: 350px; float: left; border: 10px"}

<b> Adaptive Iterative Attack towards Explainable Adversarial Robustness </b>

Current iterative attacks use a fixed step size for each noise-adding step, making further investigation into the effect of variable step size on model robustness ripe for exploration. We prove that if the upper bound of noise added to the original image is fixed, the attack effect can be improved if the step size is positively correlated with the gradient obtained at each step by querying the target model. In this paper, we propose Ada-FGSM (Adaptive FGSM), a new iterative attack that adaptively allocates step size of noises according to gradient information at each step. Improvement of success rate and accuracy decrease measured on ImageNet with multiple models emphasizes the validity of our method. We analyze the process of iterative attack by visualizing their trajectory and gradient contour, and further explain the vulnerability of deep neural networks to variable step size adversarial examples. 

![]({{ site.url }}{{ site.baseurl }}/images/respic/adv/CurlsandWhey.png){: style="width: 350px; float: left; border: 10px"}

<b> Curls & Whey: Boosting Black-Box Adversarial Attacks </b>

In this work, we propose Curls & Whey black-box attack to fix the above two defects. During Curls iteration, by combining gradient ascent and descent, we ‘curl’ up iterative trajectories to integrate more diversity and transferability into adversarial examples. Curls iteration also alleviates the diminishing marginal effect in existing iterative attacks. The Whey optimization further squeezes the ‘whey’ of noises by exploiting the robustness of adversarial perturbation. Extensive experiments on Imagenet and Tiny-Imagenet demonstrate that our approach achieves impressive decrease on noise magnitude in l2 norm. Curls & Whey attack also shows promising transferability against ensemble models as well as adversarially trained models. In addition, we extend our attack to the targeted misclassification, effectively reducing the difficulty of targeted attacks under black-box condition. 
