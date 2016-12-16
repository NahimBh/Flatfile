---
layout: page
title: Equipe
---   
<main>
<p>Test Equipe</p>   
    
{% for ligue in site.data.clubs %}
    {% for club in ligue[1 ]%}
    {{club.name}}
    {% endfor %}
{% endfor %}
</main>
