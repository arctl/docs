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
  <div class="col-md-6">


  <p class="margin-bottom-none"><a class='h4' href='{{ site.baseurl }}{{ post.url }}'>{{ post.title }}</a></p>

{% include post_details.html %}

  </div>
{% endfor %}