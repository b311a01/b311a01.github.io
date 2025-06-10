---
layout: page
title: Documents
permalink: /documents/
---
<ul>
  {% for document in site.documents %}
    <li>
    <p>{{ document.date }}</p>
      <a href="{{ document.url }}">{{ document.title }}</a>
    </li>
  {% endfor %}
</ul>