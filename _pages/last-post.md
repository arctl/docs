---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---

{% for post in site.posts limit:3 %}
{% if post.categories == "version" %}
- {{ post.date | date: "%Y.%m.%d" }}
{{ post.content }}
{% endif %}
{% endfor %}