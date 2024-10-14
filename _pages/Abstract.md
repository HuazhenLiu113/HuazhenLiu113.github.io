---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='abstract'></span>

# High-Accuracy Phase Unwrapping Based on Binarized Wrap Count
Spatial phase unwrapping is essential for converting wrapped phase fringes into a continuous unwrapped phase map, which is critical for various high-precision measurement technologies. The accuracy of phase unwrapping directly affects measurement precision. Recently, deep learning-based phase unwrapping has emerged as a promising alternative to traditional methods, primarily due to its strong resilience against noise. However, existing approaches often struggle to produce consistent results, limiting their practical applicability. This study introduces Binarized Wrap Count Phase Unwrapping (BWCPU), a novel method that utilizes neural networks to analyze phase gradient structures through binarized wrap counts. This approach reduces prediction complexity while ensuring accurate phase segmentation. In structured light surface measurements, BWCPU significantly decreases misinterpretations in noisy conditions, achieving a remarkable 76.9% improvement over leading deep learning-based wrap-count estimation methods. Furthermore, by employing a stitching algorithm known as unidirectional optimal seam stitching, BWCPU extends its capabilities to handle 1024×1024 patterns, showcasing its potential for high-precision measurements in noisy environments.


