---
layout: archive
permalink: /authors/
title: "Authors"
author_profile: false
---

<div class="grid__wrapper">
  {% for name in data.authors %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

