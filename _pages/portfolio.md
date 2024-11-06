---
layout: archive
title: "Research projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

**Natural Language Processing Research**

{% for post in site.portfolio %}
  {% if post.isresearch == "yes" %}
  	{% if post.isnlp == "yes" %}
    		{% include archive-single.html %}
    	{% endif %}
  {% endif %}
{% endfor %}

**Computer Vision Research**

{% for post in site.portfolio %}
  {% if post.isresearch == "yes" %}
  	{% if post.iscv == "yes" %}
    		{% include archive-single.html %}
    	{% endif %}
  {% endif %}
{% endfor %}
