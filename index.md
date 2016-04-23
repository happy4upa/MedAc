---
layout: page
title: Привет!
tagline: Supporting tagline
lang: ru
---

Русский вариант первой старницы

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Sample Posts

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


