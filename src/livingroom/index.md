---
layout: base
title: Chris Pages with the "Living Room" Tag
---

<h1>Living Rooms</h1>

<div class="family-grid">
  {% for page in collections.livingroom %}
  <div class="family-image">
    <a href="{{page.url}}">
      <figure>
          <img src="/images/{{page.data.livingroom}}" alt="{{livingroomAlt}}">
          <figcaption><a href="{{page.data.creditLink}}">{{page.data.credit}}</a></figcaption>
      </figure>
    </a>
</div>
{% endfor %}
</div>
