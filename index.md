---
title: Store
layout: products
---

<p>Bienvenue sur la page d'accueil !<br />
Voici mes différents cours:</p>

{% for product in site.products %}
  {% include product.html %}
{% endfor %}