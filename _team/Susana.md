---
title: "Susana Rocha"
collection: team
subcollection: PI
header:
  teaser: profileSR.png
tags: PI
tagline: Molecular Imaging and Photonics
date: 2019-08-01
email: 'susana.rocha@kuleuven.be'
website: 'susanarocha.github.io'
---


<p align= "justify">
<h2> Expertise </h2>
* Synthetic hydrogels for 3D cultures<br>
* Nanoparticle-mediated delivery<br>
* Fluorescence labelling and microscopy<br>


<p align= "justify">
<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Susana Rocha" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
