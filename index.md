---
title: The Chong Lab
layout: single
share: true
related: false
---
## Department of Chemistry at the University of Pittsburgh

//{% include figure image_path="/assets/images/westpa2-cover_hybrid.tiff" alt="Chong Research Group" %}

We are a collaborative group of scientists who work at the interface of chemistry, physics, and biology to explore the role of dynamics and kinetics in the function of biomolecules. We focus on the development and application of advanced simulation methods to generate atomistic views of rare events in biology (e.g., protein binding and large-scale transitions in proteins). We also develop simulation strategies for rational enhancement of protein switching kinetics. We are the primary developers of the [WESTPA](https://westpa.github.io/westpa) software for weighted ensemble simulations of rare events and implicitly polarized [AMBER](https://ambermd.org) force fields (ff15ipq/ff15ipq-m).

<h2><a href="/news/" style="color:inherit; text-decoration:none">{{ site.data.ui-text[site.locale].recent_posts | default: "Recent News" }}</a></h2>

<div class="grid__wrapper">
  {% for post in site.posts limit: 4 %}
      {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
