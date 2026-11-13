---
layout: default
title: Publications
permalink: /
---
{% for p in site.papers %}
  {% include paper-card.html paper=p %}
{% endfor %}
