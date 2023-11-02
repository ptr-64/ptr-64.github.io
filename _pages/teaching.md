---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.teaching %}
  {% capture year %}{{ psot.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}
