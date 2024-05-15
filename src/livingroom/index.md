---
layout: base
title: Chris Pages with the "Living Room" Tag
---

<h1>Pages Tagged with "livingroom"</h1>

<ul>
  {% for page in collections.livingroom %}
    <li><a href="{{ page.url }}">{{ page.data.title }}</a></li>
  {% endfor %}
</ul>
