---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /research/
redirect_to:
  - https://henriqueslab.org/pages/research
---
{% include base_path %}

<div class="grid">
  <div class="wrapper">
    {% for post in site.research %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
