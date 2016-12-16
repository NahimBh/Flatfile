---
layout: default
title: Blog
---

{% for post in site.posts limit:3 %}
<h2>{{ post.title }}</h2>
<p>{{ post.content }}</p>
{% endfor %}
 
{{ site.collections }}