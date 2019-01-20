---
title: Christian Kenngott
layout: actor 
---
<ul>
    {% for rollen in site.stuecke %}
        <li> <a href= "{{rollen.url}}">{{rollen.title}}</a></li>
    {% endfor %}
</ul>
