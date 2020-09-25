---
title: "Frederik De Smet"
collection: team
subcollection: PI
header:
  teaser: frederik.png
tags: PI
tagline: Translational Cell and Tissue Research Unit
date: 2019-04-01
email: 'frederik.desmet@kuleuven.be'
website: 'https://www.lpcm.be/'
---


<p align= "justify">
<h2> Expertise </h2>
* Brain cancer derived models (glioblastoma)<br>
* Multiplexed protein analysis <br>
* Crispr/Cas screening <br>

<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Frederik De Smet" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
