---
title: "Hugo Vankelecom"
collection: team
subcollection: PI
header:
  teaser: Hugo2020.png
tags: PI
tagline: Cluster of Stem Cell and Developmental Biology (SCDB)
date: 2019-02-01
email: 'hugo.vankelecom@kuleuven.be'
---


<p align= "justify">
<h2> Expertise </h2>
* Developing organoid models
* Developing complex organoid models and organoid-based tissue mimics
* Applying organoid models (e.g. tissue biology and pathology; drug and toxicity screening)

<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Hugo Vankelecom" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
