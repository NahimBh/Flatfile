---
title: Accueil
layout: default
---

<p>Bienvenue sur la page d'accueil !<br />
Vous trouverez sur ce site la boutique de la marque Bigami ainsi que mes différents cours.</p>

{% for product in site.products %}
  {% include product.html %}
{% endfor %}
