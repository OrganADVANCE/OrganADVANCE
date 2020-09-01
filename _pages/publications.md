---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
{% include base_path %}

This project will start on January 2021. Here the most relevant publications of each research group are listed.


<ul>
{% for post in site.publications reversed %}

  {% assign currentdate = post.date | date: "%Y" %}
  {% if currentdate != date %}
    {% unless forloop.first %}</ul>{% endunless %}
    <h2 id="y{{post.date | date: "%Y"}}"><span style="color:gray">{{ currentdate }}</span></h2>
    <ul>
    {% assign date = currentdate %}
  {% endif %}
  {% if post.authors contains 'Susana Rocha' %}
    {% include archive-single-pub.html %}
  {% endif %}
  {% if forloop.last %}</ul>{% endif %}

{% endfor %}
