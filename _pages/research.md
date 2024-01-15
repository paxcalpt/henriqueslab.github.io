---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
{% include base_path %}

{::options parse_block_html="true" /}
<meta http-equiv = "refresh" content = "1; url = https://henriqueslab.org/pages/research" />

<div class="grid">
  <div class="wrapper">
    {% for post in site.research %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
