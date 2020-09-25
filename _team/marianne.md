---
title: "Marianne Carlon"
collection: team
subcollection: PI
header:
  teaser: marianne.png
tags: PI
tagline: Molecular Virology and Gene Therapy
date: 2019-02-01
email: 'marianne.carlon@kuleuven.be'
website: 'https://gbiomed.kuleuven.be/english/research/50000715/50488973/molmed/Molecular-Virology-and-Drug-Discovery/cystic-fibrosis'
---


<p align= "justify">
<h2> Expertise </h2>
* Studying cystic fibrosis pathophysiology and cell molecular defects (processing, trafficking, ion channel activity) in cell lines and organoid models <br>
* Assay development for phenotypic drug screens using high content imaging<br>
* Experienced in viral vector technology, including CRISPR-Cas, in organoids, for assay development and as a therapeutic strategy for cystic fibrosis<br>

<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Marianne S. Carlon" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
