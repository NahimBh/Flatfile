---
layout: default
title: Accueil
---   
<main>
 <p>Ceci est un test</p>   
 
 {% for post in site.posts limit:3 %}
 <h2>{{ post.title }}</h2>
 <p>{{ post.content }}</p>
 {% endfor %}
 
 {{ site.collections }}
</main>