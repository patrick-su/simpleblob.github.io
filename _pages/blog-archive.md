---
layout: archive
title: "Blog and Projects"
permalink: /blog/
author_profile: true
---

{% include base_path %}
{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}
