---
title: The Chong Lab
layout: single
share: true
related: false
---
## Department of Chemistry at the University of Pittsburgh

{% include figure image_path="/assets/images/titlepic.jpg" alt="Protein Ligand Binding" %}

We are a collaborative group of scientists who work at the interface of chemistry, physics, and biology to investigate how molecular dynamics and kinetics govern biomolecular function. Our research emphasizes the development and application of advanced simulation methods to capture atomistic views of rare biological events, such as protein binding and large-scale conformational transitions. We also develop simulation strategies to rationally modulate protein switching kinetics. Our group is the primary developer of [WESTPA](https://westpa.github.io/westpa), a software package for weighted ensemble simulations of rare events, as well as the implicitly polarized [AMBER](https://ambermd.org) force fields (ff15ipq/ff15ipq-m).

<h2><a href="/news/" style="color:inherit; text-decoration:none">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent News" }}</a></h2>

<div class="grid__wrapper">
  {% for post in site.posts limit: 4 %}
      {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
