---
title: "A novel open-source ultrasound dataset with deep learning benchmarks for spinal cord injury
localization and anatomical segmentation"
subtitle: "Avisha Kumar, Kunal Kotkar, Kelly Jiang, Meghana Bhimreddy, Daniel Davidar, Carly Weber-Levine, Siddharth Krishnan, Max Kerensky, Ruixing Liang, Kelley K. Leadingham, Denis Routkevitch, Andrew Hersh, Kimberly Ashayeri, Ian Suk, Jennifer Son, Nicholas Theodore, Nitish Thakor, and Amir Manbachi"
excerpt: ""
date: 2024-07-01
author: ""
location: ""
featured: true
draft: false
# layout options: single, single-sidebar
layout: single
categories:
- Arxiv
links:
- icon: door-open
  icon_pack: fas
  name: paper
  url: https://drive.google.com/file/d/1otrYnF3cGf_1m4gznu51OO2nVQTdyTAi/view?usp=sharing
---
Abstract: While deep learning has catalyzed breakthroughs across numerous domains, its broader adoption in clinical settings is inhibited by the costly and time-intensive nature of data acquisition and annotation. To further facilitate medical machine learning, we present an ultrasound dataset of 10,223 Brightness-mode (B-mode) images consisting of sagittal slices of porcine spinal cords (N=25) before and after a contusion injury. We additionally benchmark the performance metrics of several state-of-the-art object detection algorithms to localize the site of injury and semantic segmentation models to label the anatomy for comparison and creation of task-specific architectures. Finally, we evaluate the zero-shot generalization capabilities of the segmentation models on human ultrasound spinal cord images to determine whether training on our porcine dataset is sufficient for accurately interpreting human data. Our results show that the YOLOv8 detection model outperforms all evaluated models for injury localization, achieving a mean Average Precision (mAP50-95) score of 0.606. Segmentation metrics indicate that the DeepLabv3 segmentation model achieves the highest accuracy on unseen porcine anatomy, with a Mean Dice score of 0.587, while SAMed achieves the highest Mean Dice score generalizing to human anatomy (0.445). To the best of our knowledge, this is the largest annotated dataset of spinal cord ultrasound images made publicly available to researchers and medical professionals, as well as the first public report of object detection and segmentation architectures to assess anatomical markers in the spinal cord for methodology development and clinical applications. 