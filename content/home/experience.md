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
  - title: Research assistant, Autonomous vehicles
    company: CNRS
    company_url: 'https://www.cnrs.fr/en'
    company_logo: cnrs
    location: Compiègne, France
    date_start: '2022-09-01'
    date_end: ''
    description: |2-
        Research topic: Car localization with centimeter-level accuracy      

        * Developing a deep learning based algorithm for street lamps detection to determine the vehicle position on a map.
        * Generating automatically labelled training data by projecting the poles from a map into the vehicle frame.

        Skills: Deep Learning, Weakly-supervised learning, ROS

  - title: Research project, 3D Computer Vision 
    company: Université de Technologie de Compiègne
    company_url: 'https://www.hds.utc.fr/en/research/research-teams/syri-robotic-systems-in-interaction.html'
    company_logo: utc
    location: Compiègne, France
    date_start: '2022-02-01'
    date_end: '2020-06-30'
    description: |2-
        Research topic: Partial LiDAR point clouds completion:
        • Reimplemented and compared state of the art deep learning methods for LiDAR point clouds completion.
        • Deployed these algorithms on the lab’s vehicles for real-world testing.
        
        Skills: Deep Learning, 3D Computer Vision, PyTorch

  - title: Deep Learning Research Intern 
    company: Scortex
    company_url: 'https://scortex.io'
    company_logo: scortex
    location: Paris, France
    date_start: '2022-02-01'
    date_end: '2020-07-01'
    description: |2-
        6 months research internship on Deep Unsupervised Anomaly Detection.
        Goal: Improve defect detection on industrial parts.

        • Co-authored a heuristic to remove defective parts in a fully unlabelled dataset with 90+ AUC.
        • Fine-tuned pre-trained networks with self-supervision to improve defect detection AUC from 91.6 to 96.1 points.
        
        Skills: TensorFlow, Computer Vision, Machine Learning, Deep learning

design:
  columns: '2'
---
