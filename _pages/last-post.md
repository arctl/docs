---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---


### Публикации 1

{% for post in site.posts limit:3 %}

{% if post.date != "9999-12-31" %}
- {{ post.date | date: "%Y.%m.%d" }}{% if post.author %} | {{ post.author }}{% endif %}
  {{ post.content | strip_html | truncatewords:50 }}
{% endif %}
{% endfor %}

