---
layout: archive
title: "Publications and Presentations"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

Publications
-------------

{% for post in site.publications reversed %}
  {% if post.ispaper == "yes" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

Presentations
----------------

{% for post in site.publications reversed %}
  {% if post.ispaper == "no" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
