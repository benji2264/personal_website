---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
# - title: AI Research Intern, Foundation Models
#   company: Bosch Research
#   company_url: 'https://dream.georgiatech-metz.fr/'
#   company_logo: bosch-logo
#   location: Singapore, Singapore
#   date_start: '2023-01-01'
#   date_end: ''
#   description: |2-
#       6-month internship working on state-of-the-art self supervised contrastive learning of image representations. Here, my work has focused on using foundation models (like SAM) to select better views for contrastive learning (which is usually done randomly). This work was accepted at a NeurIPS 2023 workshop [1], and another paper is under review at CVPR 2024 [2]. I also invented a method for batch image annotation (pending patent) [3]. 

#       [1] B. Missaoui, C. Yuan, "SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling" (Accepted at NeurIPS'23 workshop)
#       [2] B. Missaoui, C. Yuan, T. Ngo "Towards disambiguated self-supervised learning" (Under review at CVPR 2024)
#       [3] T. Ngo, B. Missaoui et al., Automated Image Annotation Method And System (EU patent)
- title: Research project, 3D Computer Vision
    company: Georgia Tech-Europe
    company_url: 'https://dream.georgiatech-metz.fr/'
    company_logo: gt-logo
    location: Metz, France
    date_start: '2023-01-01'
    date_end: ''
    description: |2-
        Research topic: a study of Neural Radiance Fields (NeRFs) for novel view synthesis of hyperspectral images.

        * Studying the extension of NeRFs to semi-transparent objects.

        Skills: 3D reconstruction, Computer Graphics

  - title: Research assistant, Autonomous vehicles
    company: CNRS
    company_url: 'https://www.cnrs.fr/en'
    company_logo: cnrs-logo
    location: Compiègne, France
    date_start: '2022-09-01'
    date_end: '2023-01-01'
    description: |2-
        Research topic: Car localization with centimeter-level accuracy.    

        * Studied the applications of Object Detections models to 2D points data.
        * Generated automatically labelled training data by projecting the poles from a map into the vehicle frame. (Paper under review at IEEE IV 2023)

        Skills: Deep Learning, Weakly-supervised learning, ROS

  - title: Research project, 3D Computer Vision 
    company: Université de Technologie de Compiègne
    company_url: 'https://www.hds.utc.fr/en/research/research-teams/syri-robotic-systems-in-interaction.html'
    company_logo: utc-logo
    location: Compiègne, France
    date_start: '2022-02-01'
    date_end: '2022-06-30'
    description: |2-
        Research topic: Partial LiDAR point clouds completion.

        * Reimplemented and compared state of the art deep learning methods for LiDAR point clouds completion.
        
        Skills: Deep Learning, 3D Computer Vision, PyTorch

  - title: Deep Learning Research Intern 
    company: Scortex
    company_url: 'https://scortex.io'
    company_logo: scortex-logo
    location: Paris, France
    date_start: '2021-07-01'
    date_end: '2022-01-01'
    description: |2-
        6 months research internship on Deep Unsupervised Anomaly Detection.
        Goal: Improve defect detection on industrial parts.

        * Co-authored a heuristic to remove defective parts in a fully unlabelled dataset with 90+ AUC.
        * Fine-tuned pre-trained networks with self-supervision to improve defect detection AUC from 91.6 to 96.1 points.
        
        Skills: TensorFlow, Computer Vision, Machine Learning, Deep learning

design:
  columns: '2'
---
