---
layout: archive
title: "Visual Enhancement and Analytics in Complex Scenes"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

In recent years, image processing and computer vision technologies have made tremendous progress in various applications, such as video surveillance, autonomous driving, crowd analysis, and intelligent traffic systems. However, many challenges exist in complex environments when 1) images have quality degradation and deterioration due to low light, bad weather, and data loss, or 2) images have complex content, such as dense crowds, heavy traffic, and object occlusion. These complex scenes in computer vision significantly hinder the effective use of images or videos. Therefore, sensing, enhancement, and analytics of complex visual information have become an important scientific and technological problem.


## Research Topics
1. Visual sensing: underwater sensing, ego-centric view sensing, UAV remote sensing, and multi-modality sensing.
2. Visual enhancement: underwater image restoration, low-light image enhancement, and image/video recovery with bitstream errors.
3. Visual analytics: dense crowd localization and counting, image recognition in all-weather scenes, and open-world object detection and tracking.


## Achievements
1. Image restoration in complex underwater environments
2. Image restoration in bitstream-corrupted JPEG images
3. Weakly-supervised crowd detection and counting
4. Unconstrained license plate detection and recognition


<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
