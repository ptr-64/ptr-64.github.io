---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I have been the instructor of record for UGA's Principles of Macroeconomics course in the Summer and Fall terms of '22. You can find the syllabi I used on this page. I have also served as a TA for several graduate courses, where my responsibilities included grading assignments, holding office hours to address assignments, tests, and student queries, conducting recitation classes, and teaching programming.

You can also find a summary of my teaching evaluations, and teaching philosophy [(pdf)](/teaching/teaching_statement.pdf) on this page.

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.teaching %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% include archive-single.html %}
{% endfor %}

