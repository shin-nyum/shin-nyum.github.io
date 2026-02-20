---
permalink: /diary/
title: "Diary"
layout: archive
author_profile: true
---

{% assign posts = site.categories['Diary'] %}
{% for post in posts %}
  {% include archive-single.html type="list" %}
{% endfor %}
