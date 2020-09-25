---
permalink: /
layout: archive
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
image_sliders:
  - home
---
<body align="left">

<h1 align= "center"> Welcome to OrganADVANCE!</h1>


<figure style="width: 100%" class="align-center">
<img src='/images/banner.png'>
</figure>

<h3> Advanced organoid assays for modelling human disease </h3>
<p align= "justify">
In recent years the establishment of organoid cultures derived from multiple organs has revolutionized biomedical sciences. Organoids enable scientists to provide 3D disease models preserving the genetic background of real-world patients and therefore complex disease pathogenesis. Additionally, integration of organoids in the therapeutic pipeline holds promise to reduce the use of animal models and to personalize therapeutic discovery. Yet, the full potential of organoids depends on critical innovations, such as advanced assays and imaging tools, delivery of nucleic acids and drugs to organoids and ultimately up-scaling the throughput of such assays. In order to reach such ambitious goals, it is necessary to integrate the expertise of disease and organoid specialists with the expert know-how of technology developers. **OrganADVANCE** responds to this need by bringing together top research groups from biomedical sciences with biochemists and microscopy experts at KU Leuven to drive innovations beyond the state-of-the-art in organoid research.<br>
<p align= "right">
<sup><i>The fluorescence images shown above, from different organoid models, were acquired by <a href="https://susanarocha.github.io//team/Indra/" style="color:black; text-decoration: none">Indra Van Zundert </a>).</i></sup>

<div style="text-align:left; vertical-align: middle border-left: 500px">
<h2><a href="{{site.github.url}}/news"><span style="color:gray">Latest news:</span></a></h2>
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted limit:5%}
<li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
<br>
</div>
<br>
