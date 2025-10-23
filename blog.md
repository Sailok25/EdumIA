---
layout: default
title: Blog
---

# El blog de EdumIA

Aquí encontrarás todas las guías y artículos para docentes.

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{post.url }}">{{ post.title }}</a> - {{ post.date | date: "%d %b %Y" }}
  </li>
{% endfor %}
</ul>
