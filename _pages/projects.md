---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Below is a selection of research and professional projects that I have contributed to over the years.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
