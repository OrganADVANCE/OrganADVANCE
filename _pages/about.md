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

<h1>Welcome!</h1>

<p align= "justify">

<div style="text-align:left; vertical-align: middle border-left: 500px">
<h2><a href="{{site.github.url}}/news"><span style="color:gray">Latest news:</span></a></h2>
{% assign sorted = site.news | sort: 'date' | reverse %}
{% for item in sorted limit:5%}
<li><a href="{{ item.url }}">{{ item.title }}</a></li>
{% endfor %}
<br>
</div>
<br>
