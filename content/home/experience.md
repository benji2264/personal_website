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

  - title: PhD Student, Video Understanding
    company: Nvidia
    company_url: 'https://research.nvidia.com/labs/dvl/'
    company_logo: nvidia
    location: Modena, Italy
    date_start: '2024-07-01'
    description: |2-
        Online Multi-Object Tracking with Graph Neural Networks under Dr. Laura Leal-Taixé.  

  - title: AI Research Intern, Foundation Models
    company: Bosch Research
    company_url: 'https://www.bosch-ai.com/'
    company_logo: bosch-logo
    location: Singapore, Singapore
    date_start: '2023-06-01'
    date_end: '2023-12-01'
    description: |2-
        6-month research internship on contrastive learning for images. Here, my work has focused on using foundation models (like SAM) to select better views for contrastive learning (which is usually done randomly). Accepted at NeurIPS 2023 workshop [1]. I also invented a method for batch image annotation (pending patent) [2]. 

        [1] B. Missaoui, C. Yuan, "SAMCLR: Contrastive pre-training on complex scenes using SAM for view sampling" (Accepted at NeurIPS'23 workshop)

        [2] T. Ngo, B. Missaoui et al., Automated Image Annotation Method And System (EU patent)

  - title: Research project, 3D Computer Vision
    company: Georgia Tech
    company_url: 'https://ml.gatech.edu//'
    company_logo: gt-logo
    location: Atlanta, USA
    date_start: '2023-01-01'
    date_end: '2024-05-01'
    description: |2-
        Research project on 3D reconstruction with Neural Radiance Fields (NeRFs), which we extended to be able to generate any wavelength (not just RGB). This enables all new use cases in biology and recycling, where different plants or materials exhibit different properties depending on the wavelength they are viewed from. Under review at 3DV 2025[4].
        
        [3] G. Chen,  H. Muriki, B. Missaoui, al., "HS-NeRF: HyperSpectral Neural Radiance Fields with Continuous Radiance and Transparency Spectra"  (Under review at 3DV 2025)


  - title: Research assistant, Autonomous vehicles
    company: CNRS
    company_url: 'https://www.cnrs.fr/en'
    company_logo: cnrs-logo
    location: Compiègne, France
    date_start: '2022-09-01'
    date_end: '2023-01-01'
    description: |2-
        Developed a solution fusing camera, LiDAR and IMU for projecting landmarks from 2D maps to the vehicle's camera frame, enabling to get high-quality-pseudo labeled training data for object detection models.
        
        The method was accepted at IEEE IV 2023 [5], the most prestigious conference on intelligent vehicles. 

        [4] B. Missaoui, M. Noizet, P. Xu, "Map-aided annotation for pole base detection" (Accepted at IV 2023)
  # - title: Research project, 3D Computer Vision 
  #   company: Université de Technologie de Compiègne
  #   company_url: 'https://www.hds.utc.fr/en/research/research-teams/syri-robotic-systems-in-interaction.html'
  #   company_logo: utc-logo
  #   location: Compiègne, France
  #   date_start: '2022-02-01'
  #   date_end: '2022-06-30'
  #   description: |2-
  #       Research topic: Partial LiDAR point clouds completion.

  #       * Reimplemented and compared state of the art deep learning methods for LiDAR point clouds completion.
        
  #       Skills: Deep Learning, 3D Computer Vision, PyTorch

  - title: Research Engineer Intern, Computer Vision 
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
        * Fine-tuned pre-trained networks with synthetic defects to improve defect detection AUC from 91.6 to 96.1 points.
        
design:
  columns: '2'
---
