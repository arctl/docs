---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---

{% for post in site.posts limit:3 %}
{% if post.date | date: "%Y.%m.%d" != "9999-12-31" %}
- {{ post.date | date: "%Y.%m.%d" }}
{{ post.content }}
{% endif %}
{% endfor %}