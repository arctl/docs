---
layout: last-post
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---

{% for post in site.posts limit:4 %}
{% if post.categories contains 'version' %}
- {{ post.date | date: "%Y.%m.%d" post.content }}
{% endif %}
{% endfor %}