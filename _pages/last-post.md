---
layout: default
title: "Последняя новость"
permalink: /last-post/
author_profile: false
---


### Публикации 1

{% for post in site.posts limit:2 %}
  {% include archive-single.html %}
{% endfor %}


### Публикации 2

{% for post in site.posts limit:2 %}
  
	{% include post_details.html %}

{% endfor %}