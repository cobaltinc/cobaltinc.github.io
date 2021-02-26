---
layout: page
title: Team
---

{% for item in site.data.members %}
  {% assign name = item[0] %}
  {% include member.html name=name %}
{% endfor %}