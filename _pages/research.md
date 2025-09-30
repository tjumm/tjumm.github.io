---
title: "MM Group - Research"
layout: research
excerpt: "MM Group -- Research"
sitemap: false
permalink: /research/
---

# Overview

Our research interests mainly include multimedia analysis and computing, computer vision, machine learning, and artificial intelligence. Recently, we are focusing on the visual understanding via deep learning, e.g., embodied intelligence, video/image recognition, detection and segmentation, video/image captioning, and video/image question answering (QA). We also explore the deep learning methods’ vulnerability and its robustness to adversarial attacks. Our goal is to further understand the vulnerability and interpretability of deep learning methods, which will provide theoretic evidences and methodology strategies for constructing a safer and more reliable system of image semantic understanding.

# Highlights

### 1. From Perception to Action: Embodied Intelligence in Robotic Manipulation



{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/embodied_inte/pdoc.gif" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>1 Autonomous Mobile Robotic Arm for Intelligent Perception and Grasping</b></h5>
  <p>This video showcases the latest progress in our laboratory's research on Embodied Intelligence. In the experiment, a mobile robotic arm autonomously perceives its environment, intelligently plans its path, and skillfully avoids obstacles to achieve highly efficient object grasping. This technology significantly enhances the robot's adaptability to dynamic environments by seamlessly integrating perception, decision-making, and control. It holds significant potential for applications in smart manufacturing, automated logistics, and service robotics. Moving forward, we will explore deep learning and reinforcement learning methods in embodied intelligence to equip robots with greater autonomy and generalization capabilities in complex environments.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/embodied_inte/fixed_arm.gif" class="img-responsive" width="350px" style="float: left" />
</div>

<div class="col-md-8 clearfix">
  <h5><b>2 Autonomous Robotic Arm with Multimodal Perception</b></h5>
  <p>This video showcases our laboratory's innovative research in Embodied Intelligence—a robotic arm grasping system based on multimodal perception and autonomous decision-making. By deeply integrating visual recognition, environmental modeling, and dynamic control algorithms, our method enables the robotic arm to perceive, analyze, and interact with its surroundings in real time. Through adaptive grasping strategies, it can dynamically adjust its grip based on environmental conditions, ensuring stable, precise, and efficient manipulation even in complex and unstructured scenarios. This capability is pivotal for applications in industrial automation, assistive robotics, and autonomous exploration. Looking ahead, we will continue to explore the applications of deep learning and reinforcement learning in embodied intelligence, enabling robots to achieve greater autonomy and robustness in dynamic and unknown environments.</p>
  <ul style="overflow: hidden"></ul>
</div>


### 2. Visual Understanding in Practical Scenes: Open-World Perception



{% if even_odd == 0 %}
<div class="row">
{% endif %}
<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/Causal.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>1 Novel Class Discovery for Point Cloud Segmentation via Joint Learning of Causal Representation and Reasoning</b></h5>
  <p>Yang Li, Aming Wu, Zihao Zhang, Yahong Han<br>NeurIPS 2025,<a href='https://github.com/yl6017339/Causal-NCD'>(Project Page)</a> <br>We focus on 3D-NCD, which aims to train a model for segmenting unlabeled (novel) 3D classes using only supervision from labeled (base) 3D classes. To address this, we propose imposing causal relationships as strong constraints to uncover class-aligned essential point cloud representations. We introduce a Structural Causal Model (SCM) to redefine the 3D-NCD problem and present a new method: Joint Learning of Causal Representation and Reasoning. Specifically, the method uses SCM to analyze hidden confounders in base class representations and causal links between base and novel classes; designs a causal representation prototype to eliminate confounders and capture base classes’ causal representations; and employs a graph to model causal relationships between base class causal prototypes and novel class prototypes, enabling base-to-novel causal reasoning. 
</p>
  <ul style="overflow: hidden"></ul>
</div>


<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/Continual-Adap.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>2 Continual Adaptation: Environment-Conditional Parameter Generation for Object Detection in Dynamic Scenarios</b></h5>
  <p>Deng Li, Aming Wu, Yang Li, Yaowei Wang, Yahong Han<br>ICCV 2025,<a href='https://arxiv.org/abs/2506.24063'>(Preprint)</a> <br>Environments change over time and space, challenging object detectors trained on a closed-set assumption, where training and test data share the same distribution. To address this, continual test-time adaptation has emerged, aiming to fine-tune specific parameters (e.g., BatchNorm) to improve generalization. However, fine-tuning a few parameters may degrade the representation of others, leading to performance issues. We propose a new approach that converts fine-tuning into specific-parameter generation. Our method uses a dual-path LoRA-based domain-aware adapter that separates features into domain-invariant and domain-specific components for efficient adaptation. We also introduce a conditional diffusion-based parameter generation mechanism to synthesize adapter parameters based on the current environment, avoiding local optima. Lastly, a class-centered optimal transport alignment is used to prevent catastrophic forgetting.
</p>
  <ul style="overflow: hidden"></ul>
</div>



<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/SE_COT.jpg" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>3 Style Evolving along Chain-of-Thought for Unknown-Domain Object Detection</b></h5>
  <p>Zihao Zhang, Aming Wu, Yahong Han<br>CVPR 2025, <b>(Highlights)</b>, <a href='https://arxiv.org/pdf/2503.09968'>(Preprint)</a>, <a href='https://github.com/ZZ2490/SE-COT'>(Project Page)</a> <br>In this work, we propose a new method, i.e., Style Evolving along Chain-of-Thought, which aims to progressively integrate and expand style information along the chain of thought, enabling the continual evolution of styles. Specifically, by progressively refining style descriptions and guiding the diverse evolution of styles, this method enhances the simulation of various style characteristics, enabling the model to learn and adapt to subtle differences more effectively. Additionally, it exposes the model to a broader range of style features with different data distributions, thereby enhancing its generalization capability in unseen domains. The significant performance gains over five adverse-weather scenarios and the Real to Art benchmark demonstrate the superiorities of our method.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/domain_adap/pdoc.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>4 Prompt-Driven Dynamic Object-Centric Learning for Single Domain Generalization</b></h5>
  <p>Deng Li, Aming Wu, Yaowei Wang, Yahong Han<br>CVPR 2024, <a href='http://arxiv.org/abs/2402.18447'>(Preprint)</a>, <a href='https://github.com/Daniel00008/PDOC'>(Project Page)</a> <br>In this paper, we propose a dynamic object-centric perception network based on prompt learning, aiming to adapt to the variations in image complexity. Specifically, we propose an object-centric gating module based on prompt learning to focus attention on the object-centric features guided by the various scene prompts. Then, with the object-centric gating masks, the dynamic selective module dynamically selects highly correlated feature regions in both spatial and channel dimensions enabling the model to adaptively perceive object-centric relevant features, thereby enhancing the generalization capability. Experimental results on single-domain generalization tasks in image classification and object detection demonstrate the effectiveness and versatility of our proposed method.</p>
  <ul style="overflow: hidden"></ul>
</div>


### 3. Adversarial Vision and Robustness: Towards AI Security

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/NeRF.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>1 AdvNeRF: Generating 3D Adversarial Meshes With NeRF to Fool Driving Vehicles</b></h5>
  <p> Boyuan Zhang, Jiaxu Li, Yucheng Shi, YaHong Han, Qinghua Hu<br>IEEE TIFS, <a href='DOI: 10.1109/TIFS.2025.3609180'>(Paper)</a>, <a href='https://github.com/stevenzhang9577/Adv_NeRF'>(Project Page)</a> <br>Adversarial attacks on deep neural networks (DNNs) pose risks, especially in safety-critical applications like autonomous driving. These vehicles rely on vision and LiDAR sensors for 3D perception, but adversarial vulnerabilities can mislead these systems, endangering safety. While existing research focuses on 2D-pixel image attacks, these lack real-world applicability in 3D. To address this, we propose AdvNeRF, a novel approach for generating 3D adversarial meshes targeting both vision and LiDAR models. AdvNeRF leverages Neural Radiance Fields (NeRF) to create high-quality adversarial objects, ensuring robustness across multiple viewpoints. Experimental results show that AdvNeRF significantly degrades 3D object detectors, highlighting its potential to compromise autonomous vehicle perception systems from various perspectives. This marks a key advancement in 3D adversarial attacks.
</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/CISA.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>2 Query-efficient Black-box Adversarial Attack with Customized Iteration and Sampling</b></h5>
  <p>Yucheng Shi, Yahong Han, Qinghua Hu, Yi Yang, Qi Tian <br>IEEE TPAMI, DOI:10.1109/TPAMI.2022.3169802, <a href='https://shiyuchengtju.github.io'>(Project Page)</a> <br>In this work, a new framework bridging transfer-based and decision-based attacks is proposed for query-efficient black-box adversarial attack. We reveal the relationship between current noise and variance of sampling, the monotonicity of noise compression in decision-based attack, as well as the influence of transition function on the convergence of decision-based attack. Guided by the new framework and theoretical analysis, we propose a black-box adversarial attack named Customized Iteration and Sampling Attack (CISA). CISA estimates the distance from nearby decision boundary to set the stepsize, and uses a dual-direction iterative trajectory to find the intermediate adversarial example. Based on the intermediate adversarial example, CISA conducts customized sampling according to the noise sensitivity of each pixel to further compress noise, and relaxes the state transition function to achieve higher query efficiency.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/PAR.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>3 Decision-based Black-box Attack Against Vision Transformers via Patch-wise Adversarial Removal</b></h5>
  <p>Yucheng Shi, Yahong Han, Yu-an Tan, Xiaohui Kuang <br>NeurIPS 2022, https://arxiv.org/abs/2112.03492, <a href='https://github.com/shiyuchengTJU/PAR'>(Project Page)</a> <br>In this paper, we theoretically analyze the limitations of existing decision-based attacks from the perspective of noise sensitivity difference between regions of the image, and propose a new decision-based black-box attack against ViTs, termed Patch-wise Adversarial Removal (PAR). PAR divides images into patches through a coarse-to-fine search process and compresses the noise on each patch separately. PAR records the noise magnitude and noise sensitivity of each patch and selects the patch with the highest query value for noise compression. In addition, PAR can be used as a noise initialization method for other decision-based attacks to improve the noise compression efficiency on both ViTs and CNNs without introducing additional calculations. Extensive experiments on three datasets demonstrate that PAR achieves a much lower noise magnitude with the same number of queries.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/adv/PDAN.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>4 Polishing Decision-based Adversarial Noise with a Customized Sampling</b></h5>
  <p>Yucheng Shi, Yahong Han, Qi Tian <br>CVPR 2020, <a href='https://openaccess.thecvf.com/content_CVPR_2020/html/Shi_Polishing_Decision-Based_Adversarial_Noise_With_a_Customized_Sampling_CVPR_2020_paper.html'>(Project Page)</a> <br>In this paper, we demonstrate the advantage of using current noise and historical queries to customize the variance and mean of sampling in boundary attack to polish adversarial noise. We further reveal the relationship between the initial noise and the compressed noise in boundary attack. We propose Customized Adversarial Boundary (CAB) attack that uses the current noise to model the sensitivity of each pixel and polish adversarial noise of each image with a customized sampling setting. On the one hand, CAB uses current noise as a prior belief to customize the multivariate normal distribution. On the other hand, CAB keeps the new samplings away from historical failed queries to avoid similar mistakes. Experimental results measured on several image classification datasets emphasizes the validity of our method.</p>
  <ul style="overflow: hidden"></ul>
</div>

### 4. Behavior-Level Collaborative Learning: multi-behavior recommendation

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/Recommendation/1.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>1 Latent Factor Modeling with Expert Network for Multi-Behavior Recommendation</b></h5>
  <p>Mingshi Yan, Zhiyong Cheng, Yahong Han, and Meng Wang<br>IEEE TKDE, DOI: 10.1109/TKDE.2025.3591503, <a href='https://github.com/MingshiYan/MBLFE'>(Project Page)</a><br>Traditional recommendation methods face data sparsity, while multi-behavior methods leverage diverse user data but often provide imprecise representations. To improve this, we propose MBLFE, a multi-behavior method using a gating expert network. Each expert specializes in a specific latent factor, and the gating network dynamically selects the optimal combination for each user. Self-supervised learning ensures expert independence and factor consistency. By incorporating multi-behavior data, our approach enriches embeddings and improves factor extraction. Experiments on three datasets show that MBLFE outperforms state-of-the-art methods, proving its effectiveness.
 </p>
  <ul style="overflow: hidden"></ul>
</div>




<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/Recommendation/2.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>2 User Invariant Preference Learning for Multi-Behavior Recommendation</b></h5>
  <p>Mingshi Yan, Zhiyong Cheng,Fan Liu, Yingda Lyu, and Yahong Han<br>ACM Transactions on Information Systems (TOIS), DOI: https://doi.org/10.1145/3728465, <a href='https://github.com/MingshiYan/UIPL'>(Project Page)</a> <br>In multi-behavior recommendation, analyzing diverse behaviors (e.g., click, purchase, rating) helps understand users' interests. However, existing methods often ignore the balance between commonalities and individualities in user preferences, where auxiliary behaviors may introduce noise. To address this, we propose UIPL (User Invariant Preference Learning), which captures users' intrinsic interests (invariant preferences) by leveraging invariant risk minimization. We use a variational autoencoder (VAE) with an invariant risk minimization constraint, combining multi-behavior data to enhance robustness. Experiments on four datasets show UIPL outperforms state-of-the-art methods.</p>
  <ul style="overflow: hidden"></ul>
</div>

<div class="col-md-4 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/respic/Recommendation/3.png" class="img-responsive" width="350px" style="float: left" />
</div>
<div class="col-md-8 clearfix">
  <h5><b>3 Behavior-Contextualized Item Preference Modeling for Multi-Behavior Recommendation</b></h5>
  <p>Mingshi Yan, Fan Liu, Zhiyong Cheng, Jing Sun, Fuming Sun, Zhiyong Cheng, Yahong Han<br>SIGIR 2024, <a href='https://github.com/MingshiYan/BIPN'>(Project Page)</a> <a href='Behavior-Contextualized Item Preference Network for Multi-Behavior Recommendation '>(Preprint)</a> <br>Multi-behavior recommendation methods address data sparsity in traditional single-behavior approaches by leveraging auxiliary behaviors to infer user preferences. However, directly transferring these preferences can introduce noise due to variations in user attention. To tackle this, we propose Behavior-Contextualized Item Preference Modeling (BCIPM), which learns specific item preferences within each behavior and only considers relevant preferences for the target behavior. Auxiliary behaviors are used for training, refining the learning process without affecting target behavior accuracy. Additionally, pre-training initial embeddings enriches item-aware preferences, especially when target behavior data is sparse. Experiments on four datasets show BCIPM outperforms state-of-the-art models, proving its effectiveness.</p>
  <ul style="overflow: hidden"></ul>
</div>





