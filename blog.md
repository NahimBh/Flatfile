---
title: Blog
layout: default
---

{% for post in site.posts limit:5 %}
<h2>{{ post.title }}</h2>
<p>{{ post.content }}</p>
{% endfor %}
 
{{ site.collections }}
