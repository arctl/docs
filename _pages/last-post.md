---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---

{% for post in site.post %}
	{% include archive-single.html %}
{% endfor %}