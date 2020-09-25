---
title: "Zeger Debyser"
collection: team
subcollection: PI
header:
  teaser: zeger.png
tags: PI
tagline: Molecular Virology and Gene Therapy
date: 2019-01-01
email: 'zeger.debyser@kuleuven.be'
website: 'https://gbiomed.kuleuven.be/english/research/50000715/50488973/molmed/Molecular-Virology-and-Drug-Discovery'
---


<p align= "justify">
<h2> Expertise </h2>
* Viral vector technology <br>
* Assay development for phenotypic drug screens using high content imaging<br>
* Drug discovery and development<br>

<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Zeger Debyser" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
