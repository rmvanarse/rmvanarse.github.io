---
title: "Robotic Disassembly of E-waste"
excerpt: "_Robotic disassembly of electronic devices for Apple using multimodal computer vision_"
header:
  teaser: /assets/images/projects/dave.png
gallery:
  - url: /assets/images/projects/daisy1.jpg
    image_path: /assets/images/projects/daisy1.jpg
    alt: "placeholder image 1"
  - url: /assets/images/projects/daisy2.png
    image_path: /assets/images/projects/daisy2.png
    alt: "placeholder image 2"
  - url: /assets/images/projects/daisy3.png
    image_path: /assets/images/projects/daisy3.png
    alt: "placeholder image 3"
---    
This project aimed at developing an autonomous robotic system for recycling of e-waste, particularly phones, tablets and watches. This was done as a part of the **Biorobotics lab** of **Carnegie Mellon University Robotics Institute**, in collaboration with **Apple**. The work involved developing an extension to apples ‘Daisy’ and ‘Dave’ robots that autonomously disassembles electronic devices.

{% include gallery caption="Daisy and Dave robots for disassembling and recycling iPhones" %}

The project involved identifying and locating electronic components, such as cameras, screws, speakers, batteries, etc. in phones, tablets and watches. Several novel techniques were developed for synthetic dataset generation for segmentation and classification of RGB and X-ray images. These included methods that used domain randomization, synthetic deformation, slicing of CT-scans, stc. A novel classification algorithm [iCAM](https://arxiv.org/abs/2209.03509) was developed and trained using continual learning methods to progressively include new electronic devices. Novel segmentation approaches that rely on cross-attention and contrastive learning were also developed as a part of this effort.


\[[**Apple article**](https://machinelearning.apple.com/research/rgb-x-classification)\]

\[[**Carnegie Mellon article**](https://www.cmu.edu/news/stories/archives/2021/july/device-recycling.html)\]

_**Role in  Project:** Multimodal classification, semantic understanding of X-ray images, synthetic dataset generation, and designing & implementing the full ROS architecture_

