---
layout: page
title: Ensemble
menu: true
---
{% for actor in site.ensemble %}
  <ul>
        <li> <a href="{{actor.url}}">{{actor.title}}</a></li>
  </ul>
{% endfor %}