---
title: Equipe
layout: default
---

<main>
<p>Equipe</p>   
    
{% for ligue in site.data.clubs %}
    {% for club in ligue[1 ]%}
    {{club.name}}
    {% endfor %}
{% endfor %}
</main>
