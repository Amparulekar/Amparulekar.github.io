---
layout: archive
title: "Research projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}


{% for post in site.portfolio %}
  {% if post.isresearch == "yes" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

