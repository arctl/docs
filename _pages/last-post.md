---
layout: last-post
title: "Последнии новости"
permalink: /last-post/
author_profile: false
---

{% for post in site.posts limit:3 %}
{% if post.categories contains 'version' %}
<div>
    <h4>{{ post.title }} <span class="post-meta">{{ post.date | date: "от %d.%m.%Y" }}</span></h4>
    {{ post.content }}
</div>
{% endif %}
{% endfor %}