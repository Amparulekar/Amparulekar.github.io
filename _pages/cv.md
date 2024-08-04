---
layout: archive
title: "Technical Projects"
permalink: /cv/
author_profile: true
---

{% include base_path %}

Internships
-----------------------

{% for post in site.portfolio %}
  {% if post.isintern == "yes" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Academic Projects 
-----------------------

{% for post in site.portfolio %}
  {% if post.isacademic == "yes" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
