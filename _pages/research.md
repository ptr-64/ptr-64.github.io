---
layout: archive
title: "Publications"
permalink: /research/
author_profile: true
---

## Selected Peer-Reviewed Papers

{% for post in site.selected reversed %}
  {% include archive-single-research.html %}
{% endfor %}

## Other Publications

{% for post in site.research reversed %}
  {% include archive-single-research.html %}
{% endfor %}

<!-- ## Working Papers

{% for post in site.workingpapers reversed %}
  {% include archive-single-research.html %}
{% endfor %} -->
