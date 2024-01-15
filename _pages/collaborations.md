---
layout: archive
title: "Collaborations"
permalink: /collaborations/
author_profile: true
---
{::options parse_block_html="true" /}
<meta http-equiv = "refresh" content = "1; url = https://henriqueslab.org/pages/collaborations" />

{% include base_path %}

<div class="grid">
  <div class="wrapper">
    {% for post in site.collaborations %}
      {% include archive-single-proj.html type="grid" %}
    {% endfor %}
  </div>
</div>
