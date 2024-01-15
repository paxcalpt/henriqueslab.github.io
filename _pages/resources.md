---
layout: archive
title: "Resources"
permalink: /resources/
author_profile: true
---
{% include base_path %}

{::options parse_block_html="true" /}
<meta http-equiv = "refresh" content = "1; url = https://henriqueslab.org/pages/technology" />

<div class="grid">
  <div class="wrapper">
    {% for post in site.resources %}
      {% if post.type != "from_others" and post.type != "other" %}
        {% include archive-single-proj.html type="grid" %}
      {% endif %}
    {% endfor %}
  </div>
</div>

<h2>By others with our contribution</h2>
<div class="grid">
  <div class="wrapper">
    {% for post in site.resources %}
      {% if post.type == "from_others" %}
        {% include archive-single-proj.html type="grid" %}
      {% endif %}
    {% endfor %}
  </div>
</div>

<h2>Other tools</h2>
<div class="grid">
  <div class="wrapper">
    {% for post in site.resources %}
      {% if post.type == "other" %}
        {% include archive-single-proj.html type="grid" %}
      {% endif %}
    {% endfor %}
  </div>
</div>
