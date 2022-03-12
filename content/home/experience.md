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
  - title: Applied Scientist Intern
    company: Microsoft
    company_url: ''
    company_logo: microsoft_logo
    location: Washington
    date_start: '2022-06-01'
    date_end: ''
    description: |2-
      * Self-Supervised Learning Research on Cloud AI team.

  - title: Graduate Researcher
    company: kLab Rochester Institute of Technology
    company_url: "https://http://klab.cis.rit.edu/"
    company_logo: RIT_hor
    location: New York
    date_start: '2016-01-01'
    date_end: '2020-12-31'
    description: |2-
      Self-Supervised Learning, Continual Learning, Computer Vision.

  - title: Software Engineering Intern
    company: Google
    company_url: ''
    company_logo: google_logo
    location: California
    date_start: '2020-06-01'
    date_end: '2020-09-04'
    description: |2-
        * Google Geo 3D: High-Fidelity 3D Reconstruction from Satellite Imagery
        * Implemented a 3D reconstruction pipeline in C++ for camera parameter estimation and dense point cloud generation towards building a high-fidelity textured 3D reconstruction from satellite imagery.
        * Implemented image filtering algorithms in Python for texture processing, feature extraction and building contour detection, and super-resolution tasks on 30cm multi-spectral satellite imagery.


  - title: Software Engineering Intern
    company: Qualcomm
    company_url: ''
    company_logo: qualcomm_logo
    location: California
    date_start: '2019-05-19'
    date_end: '2020-09-01'
    description:  |2-
        * VR Systems: High-Fidelity Realistic Avatar Rendering from User Expressions.
        * Built OpenGL ES application in C++ for avatar rendering using OBJ files developed in Autodesk Maya.
        * Implemented eye-tracking algorithm in C++ to integrate eye tracking capabilities
        * Implemented facial landmark detection and tracking algorithm in C++ to add real-time gesture tracking capabilities
        * Worked on variational/conditional VAE to generate avatar facial texture images using TensorFlow.
        * Investigated deep learning-based methods for alternative generation of occluded facial landmarks from speech and/or occluded image.





design:
  columns: '2'
---
