---
layout: archive
title: "Research Team"
permalink: /team/
author_profile: true
---

<figure style="width: 10%" class="align-left">
<img src='/images/you.png'>
</figure>
We are searching for talented and enthusiastic PhD students to join us! <br>
<br>
<b> Interested?</b> More information in<br>
<a href="https://www.kuleuven.be/personeel/jobsite/jobs/55919836"><i>PhD project #1: </i>Making Cells Feel At Home: Matrix And Culture Medium Optimization For Organoids</a><br>
<a href="https://www.kuleuven.be/personeel/jobsite/jobs/55904969"><i>PhD project #2: </i>Gene Transfer in Human Organoid Cultures for Non-Invasive Imaging of Biological Processes</a>

<hr-bold>
<h2>Consortium</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'PI' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>


<hr-bold>
<h2>PhD students</h2>
<hr><br>
<div class="grid">
<div class="wrapper">
  {% for post in site.team %}
    {% if post.tags contains 'phd' %}
      {% include archive-single-proj.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>
</div>

<i> Waiting for applications...</i>
