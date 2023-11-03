---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I have been the instructor of record for UGA's Principles of Macroeconomics course in the Summer and Fall terms of '22. You can find the syllabi I used on this page.

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.teaching %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}
