---
layout: page
title: Blog
permalink: /blog/
---
<ul>
  {% for post in site.posts %}
    <li>
    <p>{{ post.date | date: "%b %d, %Y" }}</p>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>