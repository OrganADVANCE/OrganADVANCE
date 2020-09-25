---
title: "Peter Dedecker"
collection: team
subcollection: PI
header:
  teaser: peter.png
tags: PI
tagline: Biochemistry, Molecular and Structural Biology
date: 2019-06-01
email: 'peter.dedecker@kuleuven.be'
website: 'https://www.chem.kuleuven.be/pd/'
---


<p align= "justify">
<h2> Expertise </h2>
* Developing advanced imaging and ‘smart’ labels <br>
* High-content visualization of complex biological systems <br>


<p align= "justify">
<h2> Relevant Publications </h2>
{% for post in site.publications reversed %}
{% assign currentdate = post.date | date: "%Y" %}
 {% if currentdate <= '2020' %}
  {% if post.authors contains "Peter Dedecker" %}
    {% include archive-single-pub.html %}
  {% endif %}
 {% endif %}
{% endfor %}
