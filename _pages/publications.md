---
layout: archive
title: "Publications & Presentations"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% include base_path %}

Publications
----------------

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Presentations
----------------

{% for post in site.presentations reversed %}
  {% include archive-single.html %}
{% endfor %}
