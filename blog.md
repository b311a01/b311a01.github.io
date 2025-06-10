---
layout: page
title: Blog
permalink: /blog/
---
<ul>
  {% for post in site.posts %}
    <li>
    <p>{{ post.date }}</p>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>