---
layout: archive
title: "Techniques"
permalink: /techniques/
author_profile: false
sidebar:
  nav: "Tech"
---

{::options parse_block_html="true" /}
<meta http-equiv = "refresh" content = "1; url = https://henriqueslab.org/pages/technology" />

<div class="grid__wrapper">
  {% for post in site.maintech %}
    {% include archive-single-proj.html type="grid" %}
  {% endfor %}
</div>
