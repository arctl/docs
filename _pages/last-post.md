---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---


### Публикации

{% for post in site.posts %}
  {% include archive-single.html %}
{% endfor %}