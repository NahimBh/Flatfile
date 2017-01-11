---
title: Equipe
layout: page
---

<main>
<p>Test Equipe</p>   
    
{% for ligue in site.data.clubs %}
    {% for club in ligue[1 ]%}
    {{club.name}}
    {% endfor %}
{% endfor %}
</main>
