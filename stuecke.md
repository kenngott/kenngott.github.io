---
layout: post
title: Stücke
menu: true
---
{% for stueck in site.stuecke %}
  <ul>
  <li> <a href="{{stueck.url}}">{{stueck.year}}: {{ stueck.title }}</a></li>
  </ul>
{% endfor %}
